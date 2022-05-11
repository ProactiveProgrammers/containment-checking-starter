# Containment Checking

## Assigned: Wednesday, May 11, 2022
## Due: Wednesday, May 18, 2022

After cloning this repository to your computer, please take the following steps:

- Follow the instructions on the Proactive Programmers web site for this project
- Use the `cd` command to change into the directory for this repository
- Change into the program directory by typing `cd containmentcheck`
- Install the dependencies for the project by typing `poetry install`
- Run the program in the following fashion:
  - `poetry run containmentcheck --size 5000 --maximum 50000000 --approach list`
  - Note that this is not the only configuration you should try for your experiment
  - Note that the program will not work unless you add the required source code
  - Refer to the `writing/reflection.md` for details about designing your experiment
- Design your own experiment to measure the performance of containment checking with `in`
- Design and conduct an experiment that aims to answer at least three three
  research questions, focusing on the following key issues:
  - The data container: `set`, `list`, and `tuple`
  - The size of the data container: small values (e.g., 1 million numbers) to big
    values (e.g., 32 million numbers)
  - Whether or not the value that it being searched for is `in` the list
  - The maximum value of the numbers that are inside of the data container
- Confirm that the program is producing acceptable experimental output
- Using data values that come from running the `containmentcheck` program,
  provide answers to your three research questions, always explaining why the performance
  trends are evident in the data set
- Make sure that you frequently commit source code, technical writing, and data
  to your GitHub repository, always using descriptive commit messages
- Use a `docker run` command for your operating system to run GatorGrader
- Please be aware that performance profiling in a Docker contain may not work as expected
- Provide all of the required responses in the `writing/reflection.md` file

# 1. Overview of Tasks

This assignment focused on creating and managing Oracle Pluggable Databases (PDBs) in a multitenant Oracle environment. The tasks included:

Creating a new PDB using the required naming convention

Creating a user inside the new PDB for future coursework

Creating and deleting a temporary PDB completely

Configuring and accessing Oracle Enterprise Manager (OEM)

Preparing documentation and publishing the work on GitHub with evidence screenshots

# 2. Oracle Environment Used

The Oracle environment used in this assignment includes:

Oracle Database Version: Example: Oracle21

Database Type: Container Database (CDB) with Pluggable Databases (PDBs)

Tools Used:

SQL Developer

Oracle Enterprise Manager (OEM)

GitHub for reporting and documentation

Operating System: Windows

# 3. Explanation of Each Task
# Task 1: Create a New Pluggable Database (PDB)

In this task, I created a new PDB using the required naming convention:

PDB Name: ma_pdb_27988
Example: ma_pdb_27988

After creating the PDB, I opened it and verified that its state was READ WRITE.

Next, I switched the session into the new PDB and created a user account inside it using the required naming convention:

Username: manzi_plsqlauca_27988
Example: ma_plsqlauca_27988

This user account will be used for all future class activities and database work.

# Task 2: Create and Delete a Temporary PDB

In this task, I created a temporary PDB using the naming convention:

Temporary PDB Name: Ma_to_delete_pdb_27988
Example: ma_to_delete_pdb_27988

After creating it successfully, I verified that it existed in the list of PDBs.

Then I deleted the PDB completely using the correct deletion method including all data files, and confirmed that it no longer existed.

# Task 3: Oracle Enterprise Manager (OEM)

In this task, I configured and accessed Oracle Enterprise Manager (OEM) successfully.

Once logged in, I verified that the dashboard displayed:

The Oracle multitenant environment

The created PDB(s)

The completed tasks

My Oracle username visible on the dashboard

# Task 4: Documentation & Reporting (GitHub)

In this task, I prepared a professional report and published it on GitHub.

The GitHub repository was created using the required format:

Repository Name:oracle_pdb_ass_II_27988_Manzi

Visibility: Public

# 4. Challenges Faced and Solutions
# Challenge 1: PDB not opening after creation

Problem: After creating the PDB, it was in MOUNTED mode.
Solution: I used the correct command to open the PDB and verified it was in READ WRITE mode.

# Challenge 2: Switching container errors

Problem: I got errors when trying to create a user without switching into the correct PDB.
Solution: I used ALTER SESSION SET CONTAINER = [PDB_NAME]; before running user creation commands.

# Challenge 3: Deleting the PDB completely

Problem: The PDB remained in the list after deletion because files were not removed.Solution: I deleted it using INCLUDING DATAFILES to ensure it was removed completely.

# 5. Integrity Statement

I confirm that this work was completed by me and reflects my own effort.
All commands, screenshots, and documentation were produced by me as part of this assignment.
No part of this work was copied from another student or unauthorized source.

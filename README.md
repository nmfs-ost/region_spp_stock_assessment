# Template Repository for U.S. Stock Assessment Files

Template repository to organize and standardize files created in a stock 
assessment workflow. This repository is made to be copied using the 
"template" button found in the top right-hand corner of the homepage.

<img width="216" height="58" alt="image" src="https://github.com/user-attachments/assets/578fd630-c396-4137-a521-812baaa1ac19" />

By maintaining the folder structure and files pushed across assessments, this 
process will reduce the barrier to onboarding for new stock assessment scientists
and encourage collaboration within the agency through a familiar process.

# How-to-Use

## Repository Content

This repository is structured to house different content necessary to execute a 
stock assessment workflow from start to finish. Each folder contains an individual 
README.md file which describes which type of information to house in a given folder. 

This repository should NOT contain every part of your process; however, it 
should contain the minimum necessary scripts, information, and shareable data 
to replicate your workflow for either future you or another stock assessment 
scientist.

## Versioning

You will notice that the name of the repository does not contain any year 
identifier for the assessment. This is because the repository is intended to 
hold the current and historical assessments and their files. A viewer or user 
of the repository can access previous assessment information through the use of 
"tags" or similarly, "releases".

By tagging the end of each assessment meaning the point at which the assessment 
is finished is marked to a tag indicating the assessment year. By adding the tag 
at this last step, the state of the repository will be captured and preserved 
for future reference. This method will help you make comparisons to previous 
assessments much easier along with general navigation easier once everyone is 
familiarized with the process.

For more information on tagging in a GitHub repository see https://docs.github.com/en/repositories/releasing-projects-on-github.

### How-To Create a Release

#### Tagging in GitHub Repository

1. Ensure your repository is complete and contains all of the files for your process including the final assessment results (if possible) and the final document.
2. Navigate to the Releases page
3. Select "Create a new release"
4. In the "Tag: Select tag" field, click the drop down then select "Create new 
tag". 
5. Enter the year of the assessment (e.g., "2026") and click "Create".
6. [Optional] enter in identifying or helpful information into the release 
details OR leave empty and click "Publish release" at the bottom of the page.

At this point, you have tagged the state of your repo/assessment. If you left the 
release empty, feel free to delete it. The tag will still remain in your tags 
tab at the top of the "Releases" page.

The tag contains a zip file which will hold all of the files stored in the 
repository at that time.

This process should repeated for each assessment cycle. By doing this, you will 
have a clear historical record of the assessment for reference.

#### Tagging using command line

Tagging using the command line is much simpler than in the GitHub UI.

1. Ensure your repository is complete and contains all of the files for your process including the final assessment results (if possible) and the final document.
2. `git tag -a 2026 -m "Tagging for 2026 assessment"` (replace "2026" with your assessment year)
3. `git push`
4. Check that your tag exists by navigating to Releases > Tags in your GitHub repository.


### Additional Resources

 - https://git-scm.com/book/en/v2/Git-Basics-Tagging

# Warnings

 - Please house information associated with file permissions like passwords and 
login info on your local computer in order to maintain security and confidentiality

 


use Renv for process

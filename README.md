<!-- badges: start -->

<!-- badges: end -->

# Brown et al. 2024

**Analyzing the effect of Equlibrium Climate Sensitivity parameter uncertainty on probabilistic temperature projections** 

**Target Journal**: *Climate Dynamics* or *Environmental Research* or *Journal of Climate*

**Proposed Author List**: Joseph K Brown, Kalyn Dorheim, Abigail Snyder, Claudia Tebaldi, Steven Smith, Derek Mu, Ben Bond-Lamberty

**Abstract**:
With the current pace of global change, understanding the sensitivity of the Earth system to human influence has become increasingly crucial. Equilibrium climate sensitivity (ECS), the long-term global temperature increase for a doubling of atmospheric CO2 concentrations, provides a measure of this susceptibility but is highly uncertain. Sherwood et al. 2020 utilized multiple lines of evidence (process, historical, and paleoclimate) to estimate ECS ranges, providing a basis for the IPCC AR6 assessment which narrowed the reported likely ECS range to 2.5-4.0 °C, with a very likely range of 2-5 °C. The new ranges are a departure from Earth system model (ESM) estimates, which have shown values over 5 °C in some cases. These findings make it clear that we cannot rely solely on ESMs to project future warming, and raises the question: how does ECS uncertainty from different lines of evidence impact probabilistic climate projections under different scenarios? Here we use a simple climate model to explore the sensitivity of probabilistic climate projections to ECS parameter uncertainty derived from different lines of evidence. Through a series of experiments using Matilda, a novel probabilistic projection framework for the simple climate model Hector, we project future warming by propagating ECS uncertainty from probability distributions characterized in Sherwood et al. 2020. These experiments evaluate the influence of sequentially omitting lines of evidence from a combined probability distribution and incorporating new lines of evidence (such as emergent constraints) on global temperature projections using a simple climate model. By investigating the different ECS ranges on probabilistic climate projections, we aim to gain a better understanding of each line of evidence and its significance for enhancing the accuracy of future warming projections.

___

## Purpose
A meta-repository creates a single point of access for someone to find all of the components that were used to create a published work for the purpose of reproducibility.  This repository should contain references to all minted data and software as well as house any ancillary code used to transform the source data, create figures for your publication, conduct the experiment, and / or execute the contributing software.

## Using the template
Simply click `Use this template` on the main repository page (shows up to the left of `Clone or download`) and fill in your `Repository name`, the `Description`, select whether you want the repository to be `Public` or `Private`, and leave `Include all branches` unchecked.

## Naming your meta-repository
The following naming conventions should be used when naming your repository:  
- Single author:  `lastname_year_journal`
- Multi author:  `lastname-etal_year_journal`
- Multiple publications in the same journal:  `lastname-etal_year-letter_journal` (e.g., `human-etal_2020-b_nature`)

## Customize your `.gitignore` file
A general `.gitignore` for use with Python or R development is included.  However, you may wish to customize this to the needs of your project.  The `.gitignore` file lets Git know what to push to the remote repository and what needs to be ignored and stay local.

## Suggestions
- Don't bog down your repository with a bunch of raw data.  Instead archive and mint a DOI for your data and provide the reference in this repository with instructions for use.
- Create complete and tested documentation for how to use what is in this repository to reproduce your experiment.

## Creating a minted release for your meta-repository
It is important to version and release your meta-repository as well due to changes that may occur during the publication review process.  If you do not know how to conduct a release on GitHub when linked with Zenodo, please contact chris.vernon@pnnl.gov to get set up.  

## The meta-repository markdown template
A sample meta-repository template is provided in this repository in the file `metarepo_template.md`.  

To use it, do the following:
1. Create the template repository as mentioned above in [Using the template](#using-the-template)
2. Clone your new repository to you local machine
3. Change directories into your new meta-repository directory you just cloned
4. Run `git rm README.md` to delete this file (`README.md`) and commit it using `git commit -m 'remove instructions'`
5. Rename `metarepo_template.md` as `README.md`
6. Run `git add README.md` to stage the new file that will show up on load in your remote GitHub repository
7. Run `git rm metarepo_template.md` to remove the original template
8. Run `git commit -m 'set up new template as readme'` to set the changes
9. Run `git push` to send the changes to your remote GitHub repository
10. Modify the `README.md` file to represent your experiement and use the `add`, `commit`, `push` workflow to update your remote repository

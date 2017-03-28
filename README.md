# Statistics Reproducibility

Reproducibility is the topic of the moment. Related to what many are calling a 'crisis of science' (a term we don't agree with), articles exploring reproducibility have appeared in such disciplines as ecology, psychology, and medicine.

Many statisticians have been instrumental in these reviews, but what about introspection? We think little has been done within the statistical literature. This project aims to investigate this further. Specifically, we will look at statistics journals, and whether code/data is contained within the publication to reproduce the results.

These are the things we should consider:

- code guidelines in statistical journals
    - Do they exist?
- what types/levels of reproducibility are we interested in?
    - code/data available from author on request
    - code/data contained in the article (i.e. in pdf appendix)
    - code/data as supplementary material (still behind possible paywall)
    - code/data contained in publicly available repository (e.g. github)
    - code/data contained in publicly available repository AND with a docker image for versioning
	
## Steps

Possible steps for project:

- identify previous research (ongoing)
- design literature search
    - identify say, top 10 statistics journals?
    - timeline (2015--2016?)
    - keywords (simulation, code, ?)
- brief read-through of articles to identify suitability
    - done by all
    - e.g. check that the article actually contains data/analysis/simulations
- longer read-through of articles kept from last phase
    - ranked against criteria above
- produce summary statistics

### Our own reproducibility

We should aim to make our own literature search reproducible! (I have no idea how to do this at the moment though). Possibly done simply by recording the keywords etc. used and which database searched. Record criteria for culling this initial literature search, then record the decisions made on each article.

If possible, we should try and contain all within a docker image that generates the final pdf.

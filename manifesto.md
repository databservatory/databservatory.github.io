# A Databservatory for social and behavioral science

## Motivation

- Data is an asset, not a liability.
- Many if not most of the phenomena that are the focus of inquiry in the social and behavioral sciences involve the small contributions of factors spanning multiple levels of spatial resolution and across multiple time frames.
- The recruitment of large scale, racially, ethnically, economically, diverse samples is a huge challenge for many social and behavioral scientists.
- Most current knowledge about human behavior comes from samples of societies that are WEIRD -- Western, Educated, Industrialized, Rich, and Developed ([Henrich et al., 2010](http://dx.doi.org/10.1017%2FS0140525X0999152X)).
- Social and behavioral scientists collect data from human participants using increasingly diverse sources.
    + Wearable devices
    + Smartphones via research-specific app platforms (e.g., Apple's HealthKit)
    + Web-based survey, experimental platforms (e.g. MTurk)
    + Laboratory-based research involving computer-based tasks.
    + Brain imaging, physiological measurements, genetic profiles
    + Video and audio recordings
    + Social networks
- Most wearable device providers have created closed data ecosystems that tie device usage to the manufacturer's platform. Other sources provide data in formats that rarely meet the ideal of being Findable, Accessible, Interoperable, and Reusable ([FAIR](http://doi.org/10.1038/sdata.2016.18)).
- New techniques for discovering patterns in data are being applied to social and behavioral data, with commercial entities leading the way.
- With few exceptions, social and behavioral data collection by non-commercial, academic or medical researchers has not been able to take full advantage of advances in large-scale data mining.
- Non-commercial research in the social and behavioral sciences faces challenges in the collection, management, cleaning, visualization, analysis, and sharing of large-scale data sources.
- The requirement that non-commercial research follow strict governmentally-regulated research ethics guidelines constrains the extent to which data can be linked and shared.
- Social and behavioral science data would be more valuable if data sets collected by different researchers could be readily shared, if the data sets were organized in ways that harmonized metadata, and if the data sets included variables that allowed linkage across levels of analysis.
- Social and behavioral scientists are under increasing pressure from research [funders](http://grants.nih.gov/grants/guide/notice-files/NOT-MH-15-012.html) to share data openly and from their [peers](http://dx.doi.org/10.1126%2Fscience.aac4716) to share materials, data, and specific analytical procedures more transparently.
- Social and behavioral scientists need new ways to publish scholarly work via pre-publication review. The preprint model adopted in other fields (e.g., [ArXiv](http://arxiv.org/) and [bioRxiv](http://biorxiv.org/)) provide one approach.
- Preprint servers do not solve the problem of sharing data, materials, and validating the reproducibility of results.
- We need a new model, or really, a new integrated ecosystem.

## Components of the proposed Databservatory ecosystem

### Web portal/app-based data collection, "We-R(esearch)-Penn-State; http://we-r.psu.edu"

- Research participants choose to affiliate
- Receive individualized data dashboards, opportunities to participate in research protocols.
- Receive compensation/rewards from researchers.
- Receive pre-publication research reports about findings.
- Opportunities to participate in commercial research.
- Researchers can develop new behavioral protocols that take full advantage of the sensor arrays available on smart phones, laptop and desktop computers.
- Researchers can "push" protocols to prospective participants.
- Increases number and geographic diversity of potential participants.
- Participants motivated by affiliation with a recognized not-for-profit academic institution.
- Individual participants can manage who has access to their data (e.g., <https://www.datawallet.io/>)

### Web-based data repository

- Builds on Databrary.org policy framework that limits access to [authorized researchers](https://www.datawallet.io/) and seeks explicit [permission to share](https://databrary.org/access/guide/investigators/release.html).
- Reduces gaps between data collection, curation, management, and the difficulty of future data sharing
- Automated data ingest from smartphones, wearables, MTurk, web-based survey engines, MRI scanners, and open data sources available via web APIs.
- Standardized data formats, metadata types.
- Standardized scheme for collecting, reflecting data sharing permissions based on Databrary model for seeking permission to share video/audio.
- Centralized researcher profiles, access and project management.
- Store and share research volumes that store in one place highlights, materials, aggregated data, individual session data, links to published papers/presentations.
- Centralized service for scholars to manage, share, and show their scholarly products.

### Web-based data analysis and visualization platform

- Builds upon open, emerging standards for reproducible and transparent research.
- Web-based digital notebook, literate programming environments such as Jupyter notebooks, RStudio/RMarkdown
- Bring analyses to data, not data to analysts. Reduces bandwidth problems in data transfer.
- Enables smart linking of data sets across levels of analysis
    +  Link geo-coded data with that collected in laboratories.
    +  Respect participants' permission for sharing potentially identifiable data (see Databrary access model, Openhumans.org, Personalgenomes.org)
- Testbed for new data mining, analysis, visualization algorithms.
- Open APIs.

### Next generation publication frameworks

- Preprint server with DOIs.
    + Preprint servers ArXiv, bioRxiv an emerging way to share, seek pre-review of scholarly manuscripts in some fields. 
    + Rare in social and behavioral science.
    + Preprints automatically linked to volume with underlying data and materials.
- "Psychological Evidence", a new journal.
    + The simultaneous publication of commentary, data, materials and displays, analysis/simulation code.
    + The capacity of pre/post publication reviewers and readers to run/re-run an authors' analyses on data using Databservatory servers or cloud-based VMs spun up for this purpose.
    + Capacity to spawn commentary threads based on pre/publication comments, including the re-running of analyses or models based on parameter changes.
    + Full version control over manuscript text, data, analysis code.
    + No anonymous comments in pre/post review. 
    + Stack Exchange-like up/down voting of articles, data sets, analyses, visualizations, and commentary.
- Next generation journal platform infrastructure could be adapted for other fields.


[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

# Awesome Sustainable Finance with stars

A curated list of **sustainable finance** resources.

# Description

The focus of the awesome sustainable finance list is:

* on open source code (software), whether this concerns tools, libraries, frameworks etc. that support any type of sustainable finance effort, and
* on open data that are useful in a sustainable finance context.

Are you interested to contribute to this collection of sustainable finance resources? [Here is how](CONTRIBUTING.md). Interested in the technical background to the list, read the [About](About.md) document.

![Solarpunk Flag](./Solarpunk_Flag.png)

Image Credit: StarwallOfRadical.town, [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0), via Wikimedia Commons

# Classification

As the list grows we may introduce more / different sub-categories. The current classification is as follows:

* [Open Source Frameworks](#open-source-frameworks)
  * [Climate Finance](#climate-finance)
  * [Carbon Footprint](#carbon-footprint)
    * [Cloud Carbon Footprints](#cloud-carbon-footprints)
  * [Biodiversity Finance](#biodiversity-finance)
  * [Circular Economy](#circular-economy)
  * [Integrated Assessment Models](#integrated-assessment-models)
  * [Social Finance](#social-finance)
    * [Financial Inclusion](#financial-inclusion)
    * [Financial Literacy](#financial-literacy)
* [Open Data](#open-data)
  * [GHG Emissions](#ghg-emissions)
  * [Energy System](#energy-system)
  * [Other Sustainability Data](#other-sustainability-data)
* [Related Domains](#related-domains)

# Open Source Frameworks

This section focuses on projects  (Models and Tools) that are primarily code oriented (models, tools etc.). Projects are grouped by domain.

## Climate Finance

Frameworks and tools that are *directly* assisting the analysis of financial operations (e.g., transactions, securities, portfolios of contracts etc.) from a climate finance perspective

* [blockchain-carbon-accounting](https://github.com/hyperledger-labs/blockchain-carbon-accounting) ⚠️ Archived - This project implements blockchain applications for climate action and accounting, including emissions calculations, carbon trading, and validation of climate claims. It is part of the Linux Foundation's Hyperledger Climate Action and Accounting SIG.
* [SBTi Temperature Alignment tool](https://github.com/ScienceBasedTargets/SBTi-finance-tool) ⭐ 63 | 🐛 18 | 🌐 Python | 📅 2026-08-13 - This toolkit helps companies and financial institutions to assess the temperature alignment of current targets, commitments, and investment and lending portfolios, and to use this information to develop targets for official validation by the SBTi.
* [Equinox](https://github.com/open-risk/equinox) ⭐ 52 | 🐛 7 | 🌐 JavaScript | 📅 2026-08-18 - Equinox is an open source platform that supports the holistic risk management of sustainable finance projects.
* [open-climate-investing](https://github.com/opentaps/open-climate-investing) ⭐ 51 | 🐛 9 | 🌐 JavaScript | 📅 2022-10-20 - Application and data for analyzing and structuring portfolios for climate investing.
* [PACTA](https://github.com/2DegreesInvesting/PACTA_analysis) ⚠️ Archived - Run the PACTA analysis on EQ & CB portfolios.
* [climate-finance](https://github.com/ONEcampaign/climate-finance-package) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2026-08-13 - climate-finance is the python package to get, clean, and work with international public climate finance.
* [r2dii.analysis](https://github.com/2DegreesInvesting/r2dii.analysis) ⚠️ Archived - Tools to Calculate Climate Targets for Financial Portfolios.
* [OS-Climate](https://github.com/os-climate) - Open Source Solutions to Enable Climate-Smart Investing.
* [ESG Reg Reporting](https://gitlab.com/finosfoundation/legend/reg-innovation/esg-reg-reporting) - A FINOS project to enable banks to consume 3rd party ESG data for the purposes of EU regulatory reporting.

## Carbon Footprint (EEIO or LCA models)

Frameworks (via EEIO or LCA Models or Hybrid Models) that are indirectly supporting climate finance through input-output / life-cycle analysis of economic systems

* [Scafandre](https://github.com/hubblo-org/scaphandre) ⭐ 1,964 | 🐛 93 | 🌐 Rust | 📅 2026-07-19 - Energy consumption metrology agent.
* [Cloud Carbon Footprint](https://github.com/cloud-carbon-footprint/cloud-carbon-footprint) ⭐ 1,050 | 🐛 205 | 🌐 TypeScript | 📅 2026-04-23 - Cloud Carbon Footprint is a tool to estimate energy use (kilowatt-hours) and carbon emissions (metric tons CO2e) from public cloud usage.
* [openLCA](https://github.com/GreenDelta/olca-app) ⭐ 263 | 🐛 40 | 🌐 Java | 📅 2026-08-20 - Source code of openLCA
* [pymrio](https://github.com/konstantinstadler/pymrio) ⭐ 221 | 🐛 62 | 🌐 Python | 📅 2026-06-23 - Multi-Regional Input-Output Analysis in Python.
* [OpenClimate](https://github.com/Open-Earth-Foundation/OpenClimate) ⭐ 64 | 🐛 58 | 🌐 TypeScript | 📅 2025-05-15 - A data utility for tracking climate action.
* [MARIO](https://github.com/it-is-me-mario/MARIO) ⭐ 52 | 🐛 22 | 🌐 Python | 📅 2026-07-30 - Multifunctional Analysis of Regions through Input-Output
* [pyLCAIO](https://github.com/MaximeAgez/pylcaio) ⭐ 46 | 🐛 0 | 🌐 Python | 📅 2025-07-28 - A Python class to hybridize lifecycle assessment (LCA) and environmentally extended input-output (EEIO) databases.
* [CityCatalyst](https://github.com/Open-Earth-Foundation/CityCatalyst) ⭐ 45 | 🐛 44 | 🌐 TypeScript | 📅 2026-08-21 - Open Source carbon accounting for cities.
* [US EEIO](https://github.com/USEPA/useeior) ⭐ 38 | 🐛 15 | 🌐 R | 📅 2025-09-30 - An R package for building and using USEEIO models.
* [pyspa](https://github.com/beyondepic/pyspa) ⭐ 31 | 🐛 2 | 🌐 HTML | 📅 2023-04-05 - A python package for conducting structural path analysis on square technological matrices of process or input-output data, using environmental, social and/or financial satellites
* [AWS Sustainability Insights Framework (SIF)](https://github.com/aws-solutions-library-samples/guidance-for-aws-sustainability-insights-framework) ⚠️ Archived - The AWS Sustainability Insights Framework (SIF) offers foundational software components that accelerate the design and implementation of applications to automate carbon footprint tracking.
* [OpenIO-Canada](https://github.com/CIRAIG/OpenIO-Canada) ⭐ 28 | 🐛 2 | 🌐 Python | 📅 2026-07-15 - Module to create symmetric Environmentally Extended Input-Output tables for Canada.
* [OpenIO-Canada](https://github.com/CIRAIG/OpenIO-Canada) ⭐ 28 | 🐛 2 | 🌐 Python | 📅 2026-07-15 - Module to create symmetric Environmentally Extended Input-Output tables for Canada.
* [ecospold2matrix](https://github.com/majeau-bettez/ecospold2matrix) ⭐ 21 | 🐛 8 | 🌐 Python | 📅 2022-12-16 - Class for recasting Ecospold2 LCA dataset into Leontief matrix representations or Supply and Use Tables
* [iopy](https://github.com/WWakker/iopy) ⭐ 19 | 🐛 0 | 🌐 Python | 📅 2026-06-14 - Input-output data with Python.
* [iomb](https://github.com/USEPA/IO-Model-Builder) ⚠️ Archived - Python Input-Output Model Builder.
* [emission budgets](https://github.com/floriandierickx/emission-budgets) ⭐ 11 | 🐛 7 | 🌐 Python | 📅 2026-04-24 - visualising country-specific carbon budgets
* [EXIOBASE-energy-accounts](https://github.com/Kajwan/EXIOBASE-energy-accounts) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2024-11-12 - Improving precision in an open-sourced procedure applicable to any MRIO database
* [Leontief](https://github.com/open-risk/leontief) ⭐ 5 | 🐛 0 | 🌐 C++ | 📅 2026-01-26 - Leontief is a C++ package to work with economic Input-Output models
* [cie-useeio-extensions](https://github.com/peterberr/cie-useeio-extensions) ⭐ 4 | 🐛 0 | 🌐 MATLAB | 📅 2019-11-27 - A repository for ongoing work at Yale Center for Industrial Ecology with collaborators to make extensions to USEEIO
* [Node Carbon](https://github.com/sumn2u/node-carbon) ⭐ 2 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2023-12-07 - A Node Package for Measuring Carbon Footprints.
* [GHG Country Sector](https://github.com/martindaniel4/ghg_country_sector) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2020-10-18 - Visualization of Greenhouse Gas emissions by Country and Sector
* [PyIO](https://real.illinois.edu/pyio/) - Python Module for Input-Output Analysis.

## Biodiversity Finance

* [riskmapjnr](https://github.com/ghislainv/riskmapjnr) ⭐ 29 | 🐛 1 | 🌐 Python | 📅 2024-07-12 - The riskmapjnr Python package can be used to obtain maps of the spatial risk of deforestation and forest degradation

## Circular Economy

Models and Frameworks that indirectly support sustainable finance by helping track material flows and advancing the circular economy.

* [brightway-lca](https://github.com/brightway-lca/brightway2) ⭐ 136 | 🐛 24 | 🌐 Jupyter Notebook | 📅 2025-04-10 - Brightway2 is a framework for advanced life cycle assessment calculations.
* [ODYM](https://github.com/IndEcol/ODYM) ⭐ 100 | 🐛 6 | 🌐 Python | 📅 2025-09-26 - Open Dynamic Material Systems Model.
* [PV ICE](https://github.com/NREL/PV_ICE) ⭐ 44 | 🐛 15 | 🌐 HTML | 📅 2026-08-18 - An open-source tool to quantify Solar Photovoltaics (PV) Energy and Mass Flows in the Circular Economy, from a Reliability and Lifetime approach.
* [open supply chains](https://github.com/supplychainstudies/OpenSupplyChains) ⭐ 31 | 🐛 0 | 🌐 PHP | 📅 2020-04-01 - Open source codebase behind Sourcemap that allows anyone to visualize and analyze supply chains.
* [Circular Economy Lifecycle Assessment and VIsualization (CELAVI) framework ](https://github.com/NREL/celavi) ⭐ 17 | 🐛 11 | 🌐 Python | 📅 2026-08-20 - Codebase for the Circular Economy Lifecycle Assessment and VIsualization (CELAVI) modeling framework.
* [pycirk](https://bitbucket.org/CML-IE/pycirk/src/master/) - A python package to model Circular Economy policy and technological interventions in Environmentally Extended Input-Output Analysis starting from SUTs.

## Integrated Assessment Models

Integrated economic models (for macroeconomic scenarios)

* [pyam](https://github.com/IAMconsortium/pyam) ⭐ 289 | 🐛 104 | 🌐 Python | 📅 2026-08-08 - Analysis & visualization of integrated-assessment and macro-energy scenarios.
* [premise](https://github.com/polca/premise) ⭐ 184 | 🐛 24 | 🌐 Python | 📅 2026-08-21 - PRospective EnvironMental Impact AsSEssment. Coupling the ecoinvent database with projections from Integrated Assessment Models (IAM).
* [MessageIX](https://github.com/iiasa/message_ix) ⭐ 150 | 🐛 143 | 🌐 Jupyter Notebook | 📅 2026-08-20 - MESSAGEix is a versatile, dynamic, model framework for energy-engineering-economy-environment (E4) systems research.
* [WorldDynamics.jl](https://github.com/worlddynamics/WorldDynamics.jl) ⭐ 75 | 🐛 24 | 🌐 Julia | 📅 2024-05-25 - An open-source framework written in Julia for global integrated assessment models.
* [mimi](https://github.com/mimiframework/Mimi.jl) ⭐ 72 | 🐛 82 | 🌐 Julia | 📅 2026-08-11 - Mimi is a Julia package that provides a component model for integrated assessment models.
* [WITCH](https://github.com/witch-team/witchmodel) ⭐ 32 | 🐛 0 | 🌐 GAMS | 📅 2025-06-06 - World Induced Technical Change Hybrid model.
* [DICE](https://github.com/psztorc/DICE) ⭐ 31 | 🐛 0 | 🌐 GAMS | 📅 2014-12-18 - Dynamic Integrated Climate-Economy Model of the Economics of Global Warming.
* [python-DICE](https://github.com/Shivamshaiv/Python-DICE) ⭐ 25 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2020-07-17 - Python 3.6 implementation of Dynamic Integrated Climate-Economy (DICE).
* [nomenclature](https://github.com/IAMconsortium/nomenclature) ⭐ 24 | 🐛 50 | 🌐 Python | 📅 2026-08-20 - Working with IAMC-format project definitions.
* [META](https://github.com/openmodels/META-2021) ⭐ 18 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2024-04-28 - The Model for Economic Tipping (point) Analysis
* [IAMC Tools](https://github.com/IAMconsortium/iamc) ⭐ 14 | 🐛 1 | 🌐 R | 📅 2023-09-12 - A collection of R tools for data analysis and diagnostics.
* [aneris](https://github.com/iiasa/aneris) ⭐ 5 | 🐛 12 | 🌐 Jupyter Notebook | 📅 2026-03-27 - Harmonization of Emissions Trajectories for Integrated Assessment Models.
* [DICE++](https://github.com/swillner/dicepp) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2021-07-27 - C++-Implementation of the DICE Dynamic Integrated Climate-Economy Model of the Economics of Global Warming.

## Social Finance

MicroFinance Frameworks and tools that support the social pillar of ESG, e.g. through financial inclusion and literacy tools and infrastructure

### Financial Inclusion

#### Mifos

* [Fineract](https://github.com/apache/fineract/) ⭐ 2,394 | 🐛 100 | 🌐 Java | 📅 2026-08-19 - Apache Fineract: A Platform for Microfinance.
* [mojaloop](https://github.com/mojaloop) - Open source software for creating payment platforms that will help unbanked people access digital financial services.

#### Interledger

* [rafiki](https://github.com/interledger/rafiki) ⭐ 354 | 🐛 53 | 🌐 TypeScript | 📅 2026-08-17 - An open-source, comprehensive Interledger service for wallet providers, enabling them to provide Interledger functionality to their users.
* [interledger-rs](https://github.com/interledger/interledger-rs) ⭐ 204 | 🐛 88 | 🌐 Rust | 📅 2023-06-16 - An easy-to-use, high-performance Interledger implementation written in Rust
* [web-monetization](https://github.com/interledger/web-monetization-extension) ⭐ 150 | 🐛 19 | 🌐 TypeScript | 📅 2026-08-22 - An open-source browser extension that enables Web Monetization.

#### Other

* [tigerbeetle](https://github.com/tigerbeetle/tigerbeetle) ⭐ 16,873 | 🐛 124 | 🌐 Zig | 📅 2026-08-18 - The distributed financial transactions database designed for mission critical safety and performance.
* [micro-finance](https://github.com/MicroPyramid/micro-finance) ⭐ 92 | 🐛 2 | 🌐 Python | 📅 2026-01-20 - Free Micro Finance Software.
* [Tazama](https://github.com/frmscoe/) - Open Source Real-Time Transaction Monitoring Software for Fraud and Money Laundering Detection.

### Social Vulnerability

* [SVInsight](https://github.com/mdp0023/SVInsight) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2024-11-26 - A python package for calculating an exploratory social vulnerability index (SVI).

### Financial Literacy

* [PLACEHOLDER](https://example.com) - TODO

# Open Data

This section collects open data sources (API endpoints) with data relevant directly or indirectly for sustainable finance workflows

## GHG Emissions

* [FaIR](https://github.com/OMS-NetZero/FAIR) ⭐ 158 | 🐛 32 | 🌐 Python | 📅 2026-07-27 - FaIR (the Finite-amplitude Impulse-Response) climate model is a simple climate model, or emulator, useful for producing global mean temperature projections from a wide range of emissions or prescribed forcing scenarios
* [openGHG](https://github.com/openghg/openghg) ⭐ 46 | 🐛 254 | 🌐 Python | 📅 2026-08-21 - A cloud platform for greenhouse gas (GHG) data analysis and collaboration.
* [climate\_categories](https://github.com/pik-primap/climate_categories) ⭐ 17 | 🐛 8 | 🌐 Python | 📅 2026-08-17 - Commonly used codes, categories, terminologies, and nomenclatures used in climate policy analysis in a nice Python package.
* [GHG Data](https://github.com/sphericalpm/ghgdata) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2017-10-31 - Greenhouse gas emissions data packaged for easy exploration and charting
* [EDGAR](https://edgar.jrc.ec.europa.eu/emissions_data_and_maps) - European Commission Emissions Database for Global Atmospheric Research
* [European Environment Agency](https://data.europa.eu/data/datasets/dat-2-en?locale=en) - EU Member States' greenhouse gas (GHG) emission projections
* [EFDB](https://www.ipcc-nggip.iges.or.jp/EFDB/downloads.php) - IPCC Emission Factor Database (offline versions for MS,Apple,Linux)
* [bonsai\_ipcc](https://gitlab.com/bonsamurais/bonsai/util/ipcc) - The bonsai\_ipcc python package enables users to calculate national greenhouse gas (GHG) inventories based on the guidelines provided by the International Panel on Climate Change

## Energy System

* [electricityMap](https://github.com/electricitymap/electricitymap-contrib) ⭐ 4,023 | 🐛 125 | 🌐 Python | 📅 2026-08-21 - A real-time visualisation of the CO2 emissions of electricity consumption
  * [electricityMap Data Sources](https://github.com/electricitymap/electricitymap-contrib/blob/master/DATA_SOURCES.md) ⭐ 4,023 | 🐛 125 | 🌐 Python | 📅 2026-08-21
* [ETHOS.FINE](https://github.com/FZJ-IEK3-VSA/FINE) ⭐ 100 | 🐛 86 | 🌐 Python | 📅 2026-08-21 - Framework for Integrated Energy System Assessment
* [gridemissions](https://github.com/jdechalendar/gridemissions) ⭐ 42 | 🐛 8 | 🌐 Python | 📅 2024-07-25 - The tools in this repository power the visualization at energy.stanford.edu/gridemissions
* [GEM](https://www.gem.wiki/Main_Page) - GEM Wiki, the shared resource on all things energy: fossil fuels, renewable energy sources, environmental impacts, and the global movement to transition to a clean energy system
* [Energy Access Explorer](https://github.com/energyaccessexplorer) - Online and interactive geospatial platform that enables energy planners, clean energy entrepreneurs, donors, and development institutions to identify high-priority areas for energy access interventions.
* [Energy Systems and Energy Economics](https://gitlab.ruhr-uni-bochum.de/ee) - Ruhr-Universität Bochum (RUB) GitLab repository cd2es Cordex tools

## Other Sustainability Data

* [SDG Data Repository (UK)](https://github.com/ONSdigital/sdg-data) ⭐ 20 | 🐛 5 | 🌐 Python | 📅 2026-03-06 - Data repository for SDGs

# Broader and/or Related Domains

Other awesome lists / resources that are more indirectly relevant for sustainable finance

* [Open Sustainable Technology](https://github.com/protontypes/open-sustainable-technology#carbon-intensity-and-accounting) ⭐ 2,543 | 🐛 78 | 📅 2026-08-18 - A curated list of open technology projects to sustain a stable climate, energy supply, and natural resources
* [Awesome Fintech](https://github.com/moov-io/awesome-fintech) ⭐ 364 | 🐛 3 | 📅 2026-08-21 - A curated collection of open source fintech libraries and resources.
* [Industrial Ecology Dashboard](https://github.com/IndEcol/Dashboard) ⭐ 161 | 🐛 0 | 📅 2026-07-02 - A collection of open source projects relevant for industrial ecology practitioners, hosted on GitHub and beyond
* [Awesome Europe](https://github.com/GeiserX/awesome-europe) ⭐ 125 | 🐛 2 | 🌐 Python | 📅 2026-08-21 - A curated list of open source software for Europe - institutions, regulations, standards, and cross-border infrastructure
* [Open Climate](https://github.com/Open-Earth-Foundation/OpenClimate) ⭐ 64 | 🐛 58 | 🌐 TypeScript | 📅 2025-05-15 - Independent Climate Accounting Network in support of Paris Agreement goals
* [climate econometrics](https://github.com/atrisovic/weather-panel.github.io/) ⭐ 45 | 🐛 19 | 🌐 MATLAB | 📅 2025-03-26 - This is a repository for a practical guide to climate econometrics available at climateestimate.net
* [Climate Modeling](https://github.com/brian-rose/climlab) ⭐ 22 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-07-23 - Python package for process-oriented climate modeling
* [NTNU Course](https://github.com/iiasa/ntnu_iam_2022) ⭐ 6 | 🐛 6 | 🌐 Jupyter Notebook | 📅 2022-05-02 - NTNU Integrated Assessment Modelling Course (2022)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-22._

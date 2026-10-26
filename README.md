# OPERA Advanced Interactive Activities – Set 1 Workshop

Welcome to the repository for the **OPERA Capacity Development Advanced Interactive Activities – Set 1 Workshop**.

This repository contains the code, Jupyter notebooks, exercises, sample data, and supporting resources developed for the hands-on workshop on **using and interpreting Copernicus Marine data**.

## About the Workshop

The workshop is part of **Set 1 of the Advanced Interactive Activities** developed within the OPERA Capacity Development activities.

It is designed to provide participants with practical experience in accessing, visualizing, analyzing, and interpreting **Copernicus Marine data** through hands-on exercises and real-world oceanographic applications.

Through the workshop, participants will learn how to:

* Discover and access Copernicus Marine products and datasets;
* Download and work with Copernicus Marine data;
* Explore ocean variables using Python;
* Visualize Copernicus Marine data;
* Analyze and interpret ocean information;
* Apply Copernicus Marine data to practical oceanographic examples and use cases.

## Getting Started — Running on CryoCloud

The workshop runs entirely in the cloud on **CryoCloud**, a managed JupyterHub. You work in your browser — there is **nothing to install on your own computer**.

### Before the workshop — please do this today

You should already have a **GitHub account** and have **accepted our invitation** to the hub. In addition:

1. **Not invited yet?** If you have **not received your hub invitation**, fill out the short [Getting Started Survey](https://forms.gle/d8oP1gp9YikS2ixM8) and give us your **GitHub username** so we can add you.
2. **Copernicus Marine account.** Create a free account at [data.marine.copernicus.eu/register](https://data.marine.copernicus.eu/register).
3. **DestinE Platform account** (for ERA5 data on the Earth Data Hub). Register at [platform.destine.eu](https://platform.destine.eu/), then open the Earth Data Hub [Quota & API keys](https://earthdatahub.destine.eu/quota-api-keys#my-personal-access-tokens) page and copy your **default API key** — the long text string itself, **not** its name `edh-bearer`. Keep it somewhere safe; you will need it during the workshop.
4. **Test your access today.** You don't need to wait for the workshop day — open the hub now at **https://sessions.ggosss.org/cloud/**, sign in with **GitHub**, and let **JupyterLab** open. Have a look around.

   **Please stop your server when you finish exploring**, to free up resources:

   > Click **File** (top-left menu) → scroll down to **Hub Control Panel** → click **Stop My Server**.

### Good to know

* Data is **streamed** from Copernicus Marine wherever possible, so you don't need to download large files.
* Your work is saved in your CryoCloud home directory between sessions.
* If your internet is slow or metered, tell a facilitator — pre-staged data can be made available.

## Repository Structure

The repository will contain the materials needed for the practical activities, including:

```text
advanced-activities-set1-workshop/
│
├── notebooks/        # Jupyter notebooks used during the workshop
├── exercises/        # Hands-on exercises for participants
├── scripts/          # Supporting scripts, where needed
├── data/             # Sample data, where needed
├── resources/        # Additional workshop resources
└── README.md
```

The repository structure will evolve as the workshop materials are developed and finalized.

## For Instructors

Instructors are encouraged to use separate branches when developing or substantially modifying workshop materials. Changes should be reviewed before being incorporated into the `main` branch.

The `main` branch will contain the validated version of the workshop materials.

## About OPERA Capacity Development

**OPERA – Ocean Prediction Enhancement in Regions of Africa** is a five-year project funded by the **European Union** and implemented by **Mercator Ocean International** in the framework of the **OceanPrediction Decade Collaborative Centre (OceanPrediction DCC)**.

OPERA aims to strengthen ocean prediction capabilities in Africa by improving access to ocean prediction information, tools, knowledge, and expertise and by supporting the development of sustainable regional capacity.

**Capacity Development** is one of the core components of OPERA. The OPERA Capacity Development activities are implemented by the **Gulf of Guinea Ocean Sciences Summer School (GGOSSS)**, as technical lead, in collaboration with the **International Chair in Mathematical Physics and Applications (ICMPA-UNESCO Chair)** at the University of Abomey-Calavi, Benin.

The Capacity Development programme combines several complementary activities, including **Ocean Literacy activities, Massive Open Online Courses (MOOCs), Advanced Interactive Activities, and practical tools and resources for ocean prediction capacity development**.

The Advanced Interactive Activities provide opportunities for participants to move from foundational knowledge to practical application through webinars, hands-on workshops, exercises, and interaction with experts.

## License

Licensing information for the workshop code and materials will be provided before their public release.

## Contact

For questions related to the OPERA Capacity Development activities or these workshop materials, please contact the OPERA Capacity Development team, contact@ggosss.org.

## Hi there 👋

In this project we will create an addition to the Linux Kernel which enables developers and end-users to see and quantify the energy cost of their running software on a process level.

Such a technology is critical because it is a fundamental building block for creating and optimizing software with respect to energy consumption. Identifying the energy costs of software plays a pivotal role in environmental preservation by fostering energy-efficient computing practices. This process creates a direct link between digital behavior and its ecological impact, making the invisible energy consumption of software visible.

Similar technology is already present in the macOS kernel (https://firefox-source-docs.mozilla.org/performance/powermetrics.html) and also in Windows via the E3 estimation engine (https://devblogs.microsoft.com/sustainable-software/measuring-your-application-power-and-carbon-impact-part-1/). But, to date, it is missing in Linux, on which however the majority of the server systems and mobile phones runs.

In order to make the technology flexibly applicable it is first to be realized with the help of eBPF and afterwards as a distributed kernel module through packages of major distrubtions to make it readily available.

By providing clear, actionable data on energy consumption, we empower the tech community to make informed decisions that favor environmental sustainability, aligning technological advancement with ecological responsibility.

What we envision is that this Kernel extension makes it so easy and readily-available to quantify your software energy consumption that it enables developers to report their energy consumption directly inside their software and also aggregated on package manager sites like PyPI etc.

Currently no software comes with an information like "Minimum energy requirements", which is very typical for hardware products. However such a transparent information would really help to empower developers to choose the most energy friendly library or end-users to use the most energy friendly app.

## Join the effort

👉 Follow the green-kernel project
👉 Introduce yourself here: https://github.com/orgs/green-kernel/discussions/1
👉 Look at the project page to see what we are up to

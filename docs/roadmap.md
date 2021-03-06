---
title: "Astronomer Roadmap"
description: "Features that Astronomer plans to develop in coming months."
date: 2018-11-02T00:00:00.000Z
slug: "roadmap"
---

Below is a summary of our future release plans. If you'd like to request a feature,
visit [our Github](https://github.com/astronomer/astronomer/issues).

| Release | Features |
|---------------------------|------------|
| v0.8 | Logs tab in Orbit UI for each Airflow deployment, which will present Airflow scheduler, webserver, and worker logs. This feature introduces an Elasticsearch infrastructure dependency, and DevOps gets a Kibana dashboard with access to the log data across Airflow Deployments.<br />Pipe Airflow task logs from Elasticsearch to Airflow UI. Improves core Airflow user experience with faster page load time.<br />CLI to support .env files and automatic connection, variable, and pool creation on start.|
| v0.9 | New Container Status tab for Airflow deployments, gives end-users a view of how each part of their Airflow deployment is presently functioning.<br />Support for New Airflow RBAC model<br />Support for Kubernetes Executor<br />Support for executing remote Airflow commands with our Astro CLI<br />View All Image Tags - give end-users a view into their Docker Registry entries<br />Metrics tab for improved end-user monitoring |
| Later | Add React to Airflow UI for real-time updates<br />Adoption metrics added to UI and shipped with telemetry - user engagement, Airflow usage growth - we need to give customers and ourselves the ability to measure how well they are adopting Airflow<br />User Audit Logging (Deployments, Configuration changes) - enterprise feature to keep track of who has done what |

<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>
<!--
*** Thanks for visiting Hexaware's Jira Migration Bootstrap Kit 
*** as part of Hexaware Bootstrap Delivery Framework
*** Now its time to reuse and customize to create something AMAZING in your projects! :D
-->

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/HexaDeliveryBootstrapFramework/JiraMigrationInventoryFetch">
    <img src="images/tfs-logo.PNG" alt="Logo" width="370" height="197">
  </a>

  <h3 align="center">Hexaware's TFS Migration Bootstrap Kit </h3>

  <p align="center">
    Thanks for visiting Hexaware's TFS Migration Bootstrap Kit, which is part of our Bootstrap Delivery Framework. Now its time to refer/reuse and customize to create something AMAZING in your projects! :D
    <br />
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-tfs-migration-as-a-service-framework">Jira Migration As A Service (JMaaS) Framework</a>
      <ul>
        <li><a href="#need-for-jmaas">Need for this Framework</a></li>
      </ul>
    </li>
    <li><a href="#tfs-migration-bootstrap-kit">Jira Migration Bootstrap Kit</a></li>
    <li><a href="#About-this-repo">About This Repo</a></li>
  </ol>
</details>

## About TFS Migration As a Service Framework

<div align="center">
  <img src="images/JMaaS_Framework.png" alt="Logo" width="1022" height="459">
</div>

Overview

The TFS Migration As a Service Framework provides a structured, repeatable process for migrating Team Foundation Server (TFS) repositories and pipelines to GitHub. This framework is designed to help teams transition from TFS to GitHub seamlessly, ensuring that all repositories, pipeline configurations, and workflows are preserved and migrated to the new platform.

Key Features
Automated TFS to GitHub Migration: Automatically migrate code repositories, build pipelines, and related configurations from TFS to GitHub.
Pipeline Conversion: Convert TFS build and release pipelines to GitHub Actions workflows.
Customizable: Configure migration steps and map TFS artifacts to GitHub repositories.
Error Handling: Built-in error handling and logging to ensure a smooth migration process.
Scalable: Supports large-scale migrations for multiple repositories and pipelines.

How we intend to support our customers with this framework based on our industry experiences:
* Suggestion on the best practices to follow as we have a deeper knowledge on the platform architecture and its components design
* Bring the right experienced and fit resources for customer specific requirements
* Acceleration of the migration with our reusable, customizable bootstrap kit (Templates, Utility Scripts) and customer fit operating model

Customer Benefits:
* Best fit migration solutions without data loss, how ever may be the systems and its data structure
* Minimize the dependency on customer people/team
* Quick project kickstart and Faster migration timeline 

Of course, this is not usable as it is. It will referred or reused to customize according to customer environment and data

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## TFS Migration Bootstrap Kit

<div align="center">
  <img src="images/JMBKit.png" alt="Logo" width="805" height="381">
</div>

Components for Jira Migration Bootstrap Kit are:
* <b>Jira Migration Assessment Questionnaire & Project Management Template: </b>
  * Questionnaire which can be shared with customer for response. We can capture the response through workshop sessions and scanning through customer documents, tools.
  * ReadinessChecklist can be used for tracking project details and progress
* <b>Customizable Utility scripts: </b>
  * Custom build scripts to capture the inventory data of repo and pipeline and migration scripts
 
<p align="right">(<a href="#readme-top">back to top</a>)</p>
 
## About This Repo
This repo is structured as,

* <a href="https://github.com/HexaDeliveryBootstrapFramework/TFS2019InventoryFetch/tree/main/ReadyTemplate">Template: </a>
* <a href="https://github.com/HexaDeliveryBootstrapFramework/TFS2019InventoryFetch/tree/main/inventory_fetching_script">Inventory fetching scripts: </a> Custom build script to capture the  to fetch the inventory of repo and pipeline details
* <a href="https://github.com/HexaDeliveryBootstrapFramework/TFS2019InventoryFetch/tree/main/migration_script">Migration Script: </a> Custom build script to capture the inventory data for migration of repo

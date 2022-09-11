
# Project Title

Comment Anywhere

# Phase Leaders

*not yet decided*

Luke Bates - Analysis

Frank Bedekovich - Requirements

Robert Krency - Implementation

Karl Miller - Design

> Just throwing one possible arrangement up; I am willing to lead any phase and am not overly concerned with who leads any other phase.

# Introduction

Comment sections provide a forum for lively debate of the issues, sources of further information, and anecdotes, experiences, and advice from other readers. They can be difficult to moderate, however, and many websites have shuttered their comment sections as a result. The comments haven't stopped; they have just been outsourced to social media platforms.

# Motivation

Websites which do not have comments are missing out on user engagement. On the other hand, users are missing out on comments being associated with and "following" webpages around the internet, instead having access only to a limited subset of comments that are tethered to particular social media posts. There is a gap in the market and our product can fill that gap and capture some user screen time, which we can monetize by interpolating advertisements in our comment sections.

# Objectives

1. Extensions for Chrome and Firefox

Users can download and install an extension for Firefox or Chrome. The extension will add a button which, when clicked, will open a sidebar that displays comments associated with the URL the user is currently visiting.

2. Back End Server

Extensions will communicate with a server that will deliver data used to populate the comment sections, authenticate logins, process the registration of new users, and allow logged-in users to post new comments.

3. Database

A relational database will host comments and user login information. The Back End Server will communicate with the database.

4. Moderation Page

Users with appropriate login levels will be able to access a moderation page listing all comments that have been flagged by other users or automated processes and determine what action, if any, should be taken to moderate the comments.

5. Landing Page

A landing page will describe the project and host design documents and the downloadable extensions for Chrome and Firefox.

# Implementation Techniques

## Extensions

The Extensions will be designed according to the extension specifications of Chrome or Firefox. They will use HTML and Javascript and other components as necessary to implement the extension.

## Server

The back end server will provide a RESTful API that the front-end extension can interface with. The Back-end service will be implemented in a language well-suited for internet applications such as Java/Spring, ASP.net, or Golang.

## Database

A relational database will host comments, metrics, and user credentials. We will use a tried-and-true relational db such as Postgres SQL, MySQL, or SQLite.

## Static Pages

Some static pages will be hosted which will provide an overview of the project, change logs, design documents, and downloadable extension files. It will need to serve HTML, CSS, Images, and Files efficiently. We can use free Github Pages hosting to accomplish this.

## Docker
Building a docker image will grant us flexibility in deployment, allowing us to run the server on a variety of personal machines or, eventually, deploy it on the cloud.

# Potential Users

Any user of the internet is a potential user of our product. In particular, users who want more information about an article or webpage and users who wish to express their opinions, experiences, and knowledge are likely users of our product.

# Features and Deliverables

## Extensions

Chrome and Firefox extensions will be available to download. The extension will be capable of listing comments retrieved from the Server, facilitating user log in, and facilitating a logged-in user posting comments and flagging posts for moderation.

## Server

A back end server that can handle HTTP Requests and send HTTP Responses in JSON format will manage authorization, add new comments to the database, and allow the extensions to populate the comment sections that users can view.

## Database

The database will have a well-formatted schema and be able to efficiently query for relevant data that the Server can send. It should be able to efficiently read and write data.

## Moderation Page

A moderation page will display to a logged-in moderator comments in need of moderation and allow the moderator to decide on what actions, if any, to take on a flagged comment.

## Landing Page

A staticly hosted webpage will provide an overview of the project. It will concisely describe the utility of Comment Anywhere and provide extension download links.
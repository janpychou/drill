---
layout: post
title: "Drill 1.0 Released"
code: drill-1.0-released
excerpt: Drill 1.0 is now available, representing a major milestone for the Drill community. Drill in now production-ready, making it easier than ever to explore and analyze data in non-relational datastores.
authors: ["tshiran", "jnadeau"]
---
We embarked on the Drill project in late 2012 with two primary objectives:

* Revolutionize the query engine by enabling low-latency queries on Big Data while getting rid of all the 'overhead' - namely, the need to load data, create and maintain schemas, transform data, etc. We wanted to develop a system that would support the speed and agility at which modern organizations want (or need) to operate in this era.
* Unlock the data housed in non-relational datastores like NoSQL, Hadoop and cloud storage, making it available not only to developers, but also business users, analysts, data scientists and anyone else who can write a SQL query or use a BI tool. Non-relational datastores are capturing an increasing share of the world's data, and it's incredibly hard to explore and analyze this data.

Today we're happy to announce the availability of Drill 1.0, our first production-ready release. Drill 1.0 includes many performance and reliability enhancements over previous releases.

We would not have been able to reach this milestone without the tremendous effort by all the [committers]({{ site.baseurl }}/team/) and contributors, and we would like to congratulate the entire community on achieving this milestone. While 1.0 is an exciting milestone, it's really just the beginning of the journey. We'll release 1.1 next month, and continue with our 4-6 week release cycle, so you can count on many additional enhancements over the coming months.

We have inlcluded the press release issued by the Apache Software Foundation below.

Happy Drilling!  
Tomer Shiran and Jacques Nadeau

<hr />

# The Apache Software Foundation Announces Apache™ Drill™ 1.0

## Open Source schema-free SQL query engine revolutionizes data exploration and analytics for Apache Hadoop®, NoSQL and Cloud storage 

Forest Hill, MD - 19 May 2015 - The Apache Software Foundation (ASF), the all-volunteer developers, stewards, and incubators of more than 350 Open Source projects and initiatives, announced today the availability of Apache™ Drill™ 1.0, the schema-free SQL query engine for Apache Hadoop®, NoSQL and Cloud storage.

"The production-ready 1.0 release represents a significant milestone for the Drill project," said Tomer Shiran, member of the Apache Drill Project Management Committee. "It is the outcome of almost three years of development involving dozens of engineers from numerous companies. Apache Drill's flexibility and ease-of-use have attracted thousands of users, and the enterprise-grade reliability, security and performance in the 1.0 release will further accelerate adoption."

With the exponential growth of data in recent years, and the shift towards rapid application development, new data is increasingly being stored in non-relational, schema-free datastores including Hadoop, NoSQL and Cloud storage. Apache Drill enables analysts, business users, data scientists and developers to explore and analyze this data without sacrificing the flexibility and agility offered by these datastores. Drill processes the data in-situ without requiring users to define schemas or transform data.

"Drill introduces the JSON document model to the world of SQL-based analytics and BI" said Jacques Nadeau, Vice President of Apache Drill. "This enables users to query fixed-schema, evolving-schema and schema-free data stored in a variety of formats and datastores. The architecture of relational query engines and databases is built on the assumption that all data has a simple and static structure that’s known in advance, and this 40-year-old assumption is simply no longer valid. We designed Drill from the ground up to address the new reality.”

Apache Drill's architecture is unique in many ways. It is the only columnar execution engine that supports complex and schema-free data, and the only execution engine that performs data-driven query compilation (and re-compilation, also known as schema discovery) during query execution. These unique capabilities enable Drill to achieve record-breaking performance with the flexibility offered by the JSON document model.

"Drill's columnar execution engine and optimizer take full advantage of Apache Parquet's columnar storage to achieve maximum performance," said Julien Le Dem, Technical Lead of Data Processing at Twitter and Vice President of Apache Parquet. "The Drill team has been a key contributor to the Parquet project, including recent enhancements to Parquet types and vectorization. The Drill team’s involvement in the Parquet community is instrumental in driving the standard."

Availability and Oversight
Apache Drill 1.0 is available immediately as a free download from http://drill.apache.org/download/. Documentation is available at http://drill.apache.org/docs/. As with all Apache products, Apache Drill software is released under the Apache License v2.0, and is overseen by a self-selected team of active contributors to the project. A Project Management Committee (PMC) guides the project's day-to-day operations, including community development and product releases. For ways to become involved with Apache Drill, visit http://drill.apache.org/ and @ApacheDrill on Twitter.

About The Apache Software Foundation (ASF)
Established in 1999, the all-volunteer Foundation oversees more than 350 leading Open Source projects, including Apache HTTP Server --the world's most popular Web server software. Through the ASF's meritocratic process known as "The Apache Way," more than 500 individual Members and 4,500 Committers successfully collaborate to develop freely available enterprise-grade software, benefiting millions of users worldwide: thousands of software solutions are distributed under the Apache License; and the community actively participates in ASF mailing lists, mentoring initiatives, and ApacheCon, the Foundation's official user conference, trainings, and expo. The ASF is a US 501(c)(3) charitable organization, funded by individual donations and corporate sponsors including Bloomberg, Budget Direct, Cerner, Citrix, Cloudera, Comcast, Facebook, Google, Hortonworks, HP, IBM, InMotion Hosting, iSigma, Matt Mullenweg, Microsoft, Pivotal, Produban, WANdisco, and Yahoo. For more information, visit http://www.apache.org/ or follow @TheASF on Twitter.

© The Apache Software Foundation. "Apache", "Apache Drill", "Drill", "Apache Hadoop", "Hadoop", "Apache Parquet", "Parquet", and "ApacheCon", are registered trademarks or trademarks of The Apache Software Foundation. All other brands and trademarks are the property of their respective owners.

\# \# \#
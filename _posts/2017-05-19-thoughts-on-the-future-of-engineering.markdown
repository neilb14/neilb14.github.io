---
layout: post
title: Thoughts on the Future of Engineering Tools
categories:
- blog
tags:
- product_dev
date: 2017-05-19
---

The past decade has brought about huge improvements to Engineering software tools. Advancements in CAD, BIM and PLM have led to reduced design times, improved design quality and a reduction in total project costs. A number of forces at play over the past decade worked together to get us where we are today.

## Force Numero Uno: Digitization
Replacing paper and analog process with digital inputs and computer managed workflow has made an enormous impact to Engineering. Eliminating paper copies reduces the need for administrative roles and time consuming activities like filing and searching. It has also helped to reduce manual data entry which in turn accelerates the design process and improves data integrity. 

It also means less physical space is required for cold document storage and workspace for warm humans. Engineering can be disconnected from physical location, virtualized, distributed globally and instantly outsourced.

Digitizing the work process has also led to massive efficiencies. The ability to measure time spent on tasks has enabled lean teams to quickly identify bottlenecks and accurately forecast project schedule completion. Digitized standard work makes it quickly available for training and provides the flexibility required for lean continuous improvement activities.

## Force 2: Connecting Inputs to Outputs
Connecting data from input to output reduces the cost of change or at least makes it visible. The impact of changes to input data whether it is physical or meta can easily be handled. Computers are able to determine deltas and automatically notify stakeholders and contributors. In some cases computers can also automatically handle the impacts of change by automatically making adjustments to deliverables.

## Force 3: Increasing Dimensions of a Model
In the past decade we’ve exploited 3D CAD to support human decision making by displaying increasingly detailed and accurate model information. More dimensions to the data are being combined as Engineering tools become the confluence of contributors with the added dimension of time. One must look no further than a handful of widely available BIM case studies to see the power that a single source of truth throughout the Engineering, construction and operations lifecycle can achieve.

Intelligent decisions based on the most detailed and accurate information early will lead to optimized designs that require far less rework. Ultimately leading to reduced costs.

## Have we crossed the chasm?
Innovations of last decade seem to have made their way from being the competitive advantage of a visionary few to becoming fundamentally available in the tools employed by the majority. Standard CAD, BIM and PLM toolsets feature many of these innovations out of the box. Specific or advanced functionality is easily found in plug-ins or bolt-on tools. So it seems the entire industry has adopted a new normal. 

But the winds of change are blowing again.

## The New Force: Rapid Craft Design
Recently I came across the following diagram that changes the way I view the roadmap of Engineering tools:
![Production Volume vs. Number of Variants]({{ site.url }}/static/20170519/volume-vs-variants.png)

This diagram illustrates the movement in manufacturing to combine the flexibility of custom designs with the efficiency of mass production. In the coming years we will be able to construct many physical objects nearly instantly through componentization, robotics and 3D printing. Coupled with the driving force of lean production systems to reduce inventories using Just-In-Time fabrication there will be a great deal of pressure on the lead times for Engineering designs. Couching the trend in lean terms, Engineering will soon become the bottleneck.

In the same way the drive for digitization nudged the industry forward in the past decade using automation to dramatically reduce lead times will shape the development of Engineering tools into the future. Engineering organizations with the capability to perform custom designs in a vastly reduced timescale will realize a significant competitive advantage. Innovation in the next decade will revolve around this new force to make craft designs at the pace of mass production.

## Pull out the Crystal Ball
Here are three innovations that Engineering organizations should focus on in the years to come:

### 1. Replace human engineers with AI
When computers are involved in the design process there’s no need for a human to perform calculations or make technical design decisions. Developers can use a programmatic approach using calculations,constraints, rules and heuristics to arrive at an optimal solution. Alternatively, Case Based Reasoning can be used to quickly find the closest matching design from a set of known variants. Both of these techniques used broadly today are effective in many cases. But there are problems for which simple programming won't suffice.

When programmatic approaches fall short organizations could see success by applying traditional machine learning techniques.  This is really just the application of statistical methods iteratively over a set of inputs and outputs to define a model. With the experise of an Engineer to select the best features to train on and a modest history of design data these traditional techniques can be used to train accurate models in a short period of time.

Another option is to employ a branch of machine learning called Deep Learning. With Deep Learning, a massive number (millions) of records is presented to a Neural Network to iteratively shape the weights of nodes within the network. While Deep Learning can solve very challenging problems it requires a much deeper history of data than traditional approaches. It is true that most organizations have been collecting Engineering data for over 10 years, but the quantity may still not be sufficient to train a Neural Network. In cases where structured data (databases, spreadsheets, etc.) may be insufficient organizations will need to dig deep to make use of relevant unstructured or undigitized data they may have.

## 2. Leveraging design histories
Organizations that have an Engineering Document Management System (EDMS) will be ahead of the game because structured data can quickly be used to drive innovation. But data doesn't have to be stored in a database to be useful, in fact even paper designs can quickly be scanned and digitized using computer vision technology. Consider the years of Engineering designs retained for legal obligations.

The data doesn't have to be purely numerical either. Using Computer Vision and Natural Language Processing (NLP) organizations could extract meaningful data from unstructured text such as project specifications, regional codes and approval criteria.

In addition to machine learning described above, data can be used to simply reduce the number of design variants. In "Craft" Engineering each problem is approached as a unique event, much like a tailor creating that perfect fit. But not every problem requires a perfect fit. Most of us can't afford the time and expense required to tailor every shirt we wear to fit perfectly which is why clothing companies have T-Shirt sizes. In the same way rather than custom designing an Engineering solution teams could pick from a set of canned solutions. Or better, have software do it automatically and let a human validate the design.  A library of the most common design variants could be collected by mining the history of designs. Then, when tasked with a new design, Case Based Reasoning could be used to find a matching variant from the reduced set.

It could also be possible to reuse parts of designs by chopping them up and storing the parts in a library of reusable components. Components could be automatically selected using Case Based Reasoning, "cut and pasted" or functions to search could be integrated with CAD and BIM tools. Designers could be guided to make quick decisions with the use of recommendation engines similar to those employed by Amazon and Netflix.

Even without a rich history of in-house design information Engineering teams can make use of external data available for free or purchase. Vast sets of data are being published on open-data friendly government websites, University research sites and a multitude of data science websites. There is also a growing trend for manufacturers to syndicate product information into data catalogues that can be licensed for use in design tools. With a simple search troves of data can be found that might be put to good use towards reducing lead times in Engineering design.

## 3. Real world in real time
The heavy and diverse data requirements for the future will push the envelope on how Engineering design tools interact with other systems and inputs from the real world. Current applications require clean, structured inputs in order to provide predictable behaviour. Tools in the next decade, however, will need to accept a broad variety of inputs and have the capability to interpret fuzzy, sometimes ambiguous data from the real world.

The growing use of laser scanning and LiDAR, for instance, requires greater automation in feature extraction from point clouds. Similarly, computer vision will be exploited to extract meaningful data from photos and videos. The volume and availability of pictures, videos and point clouds is expected to increase with the growing use of field electronics and drones to capture data for survey, construction and Engineering applications. Engineering tools that ingest a variety of formats will present a significant advantage because design can commence as soon as raw footage is obtained.

Information contained in other software such as Enterprise Resource Planning (ERP), Production Scheduling and Manufacturing Execution Systems (MES) can be used to make intelligent design decisions based on current conditions. Engineering organizations that put real time pricing, labour availability, schedules and other external factors into the fingertips of design Engineers will be able to minimize total costs for customers. Integrating real time awareness of the supply chain into Engineering design tools brings huge advantages without sacrificing Engineering time.

## What's Next
With greater speed and flexibility in manufacturing and construction comes an entire set of new challenges for Engineers. Gains will be made when Engineering organizations invest in the people and tools that enable them to perform custom designs at a fast pace. In order to get there Engineering organizations must build on capabilities made widely available in the past decade, and set the objective to further reduce lead times. More innovative organizations will develop or aquire tools with the capability to:
- automate the Engineering design process
- unlock the potential inside their existing structured and unstructured data
- integrate systems to make real world and real time data available at design time

I for one am doubling down on data science and CAD/BIM tool integration and keen to see changes in the Engineering process that will take place in the decade to come.

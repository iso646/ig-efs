# Insight Global Edleman Farm Supply Presentation - Case Study
---
_Materials to share with the team, some reviewed, some were not_

## Craftsmanship
---
_Show pieces for fun and extra/bonuses_
* [Edleman Farm Supply - Power Point Show](https://iso646.github.io/ig-efs/EFS%20Case%20Study%20-%20Final.pdf)
* [Edleman Farm Supply - Interactive SVG Map](https://codepen.io/iso646/pen/pooegrJ)
* [Value-Risk Matrix - Idea Phase One](https://airtable.com/tblqmkkGOiyt6922l/viwxl6GRoSLg08BOH?blocks=hide)

## Presentation Bits
---
_Reminders and researched notes for later_

### Extracted Business Intel

* 3rd largest tractor supply
* Recently added apparel and accessories
* Slow market growth and revenue, 70 yr strategy from 1948
* COO feels CIO is stale
* Website is externally facing, out dated, meant for marketing materials on products, and a commerce platform for sales with troubleshooting guides and live chat
* 98.5% server uptime
* Maintenance is the uptime battle
* Lacking redundancy and standards in software
* Windows & LAMP applications rats nest
* Couple applications (reporting) are running in Windows server 2008 R2
* RHEL 6 and 7, with the desire to go to 8, but fear of costs
* Physical infastructure is over 7 years old
* Content Management DataBase is out of date and manual tracking of inventory is done quarterly, yet takes a complete month to resolve
* Configuration management is a combination of manual and auto processes
* Microsoft SCCM is used to deploy Windows systems in 50% instances, others fail and require manual packages

### COO Pain Points

* Wants to resolve:
    * excessive operational support
    * poor SLAs
    * costly support or licensing costs
    * any other critical issues
    * POS, Devises and tech at the 150 retail locations
    * better connection with retail allies like REI and Bass Pro
    * increase financial rentals, loans and leases for equipment
* Open to:
    * everything: says assume nothing
    * newer ideas to breath life into org
    * communication platform to gain wins with other teams

### Special to Avoid
* RHEL 8.x, support isn't there and the platform isn't solid/stable enough for a higher than 97% uptime SLA
* Too heavy of a focus on SEO/SEM, until after launching tech suite
* Software and tech packages without management and built in support
* Costly cloud only solutions when they aren't IT heavy

### Quick Ideas to Jot
* Ubuntu based platform, with Windows as an additional option, away from RHEL support costs and licensing
* KY or Southern district based hosting and server solutions provider (managed lower cost than their IT techs now) (especially fantastic if board members are older as well)
* Website updated to include significant photography of the farm, emphasizing "American" values connection since 1948
* Emphasis on marketing and UI for leases of equipment for various purposes, even city dwellers (college students)
* Local university support via internships and brand ambassador support (discounts on merchandise)
    * Special pitches over "break periods"
* Azure could be good, but expensive, same with AWS
* Slack integration with potential for heroku stack via salesforce configuration, for their sales-inventory and other solutions via POS
* May want to transition into more of a square, paypal, etc payments processor
* Present with a low, medium, and high cost solution plan
* Provide on-prem, complete cloud, and hybrid options
* Lower labor costs as much as possible
* Inventory management solution (with facts on ROI, SWOT & KPIs)
* Create a brief roadmap of what, when, where and how long it would take to do these things
* Presentating Bits
    * 3 solutions explained
    * roadmap to showcase suggested timelines
    * suggestions on continual staffing and insight globals' potential interaction post-grid
    * some sort of social media and community engagement/enrichment plan
    * interactive peice per Larry loving animation
    * bring something data-matrix like for Ryan and Cecil since they like funnelling and automation
 * Recommendations with Hootspa
    * increase social media engagements with the community and with students
    * become an internship co-op approved institution and start offering brand ambassador agreements
    * increase photography for the website, highlighting these improved engagements and the rental land/equipment, space, etc
    * targeted sales initiatives surrounding holidays, school break times and school move-in or move-out times, with either
    * strategic partnerships, or a combination and truck rentals
    * synergenistic partnerships with companies like Luckett & Farley, an architectural-engineering and interior design firm _(where they might want farm based photography, etc for trade of information on new website)_
    * obtain a service agreement/contract with a local colocation provider and reduce the coporate footprint with on-prem solutions outside of the main service areas
    * reduce technical debt regarding platforms uneeded, by way of replacing or updating/porting the reporting management software with an out-of-the-box ready-made solution OR with an application framework that can be universal _(Windows & Ubunutu, etc)_
    * Salesforce for commerce goods cloud platform, as an all-in-one customer service, sales pipe-line, agile lead gen, project management, inventory and point of purchase system, that can be integrated with almost any ERP
    * Integrate the salesforce solution with the POS, inventory, reporting, and colocation solutions offered in the previous option, AND create a strategy for growth as needed in the future, for complete cloud migration should total off-prem solution make more sense long term via a platform like the salesforce lighting distribution cloud AND/OR the heroku service offerings
    * Starts at $250/mo per user, but not every sales team member needs to be a user, also integrates with slack
    * Time and money estimations or allotments, depend on how much inventory is sitting around on deck, payment processing, shippers, and how cash strapped the business currently is or is-not

    

### Cloud & Colocation Bits
Being a company from Louisville, KY- the bluegrass state, EFS can't afford not to use a data center and some sort of serious cloud offering. Kentucky has lowest cost of electricity east of the Mississippi and one of the lowest in the continental US at nearly 20% less than the national average.

### Areas of Focus
1. Community Engagement (esp with the Farm, merchandise will follow) -- making website events, engagement and sales focused
2. Improve stability of services offered and platform SLAs
3. Improve internal communication, inventory, lead gen and sales pipeline management
4. Long term strategy for product cohesion and vision

_steps should be concurrent_

### Highlighted Staffing Needs _Per IG's Purpose_
* Reduction in labor force for lower cost "help desk" personnel responsible for purely maintenance or upgrade driven software/systems tasks
* Increase in customer service and sales facing staff needs based on more productive marketing and campaign generation management strategy
* Increase in farming location and management staff based on the community events and responses
* Increase in associates (alliance partners) for B2B and B2C alliances with companies like REI and Bass Pro Shops
* Increase in finance personnel for the loan officer role per the refocus towards the emphasis on sales, leases, rentals, etc

### Timing and Pricing
> If going with a solution like salesforce where it's out of the box and setup charges are associated, then the time is reduced. If instead the idea is to colocate servers and custom service platforms internally, costs will be reduced significantly, but the timing won't be... All other bits are conjecture, not worthy of discussion without knowing processing and gateways info.

### Salesforce Yeti Highlights to Mention
* Yeti use case with Salesforce integrations estimated about 250 employees deemed total, so even if worst case scenario, $750,000 yearly for the complete consumer goods services
* Though only about 10% max, are estimated for the amount of users that would need to be listed users or billable users on the platform, so if we instead said approximately: $75,000 for the sales cloud, service cloud, marketing cloud AND salesforce platform...
* 1 to 1 most likely regarding helpdesk techs to customer service reps (added) conversion translating to low net costs here
Salesforce commerce platform B2B is a smaller requirement with pricing in and around $20,000 per year at the higher end for a company like EFS
* Salesforce commerce platform B2C is alot more friendly than most of the other options out there, with some pricing explained via buddy Paul: https://paulnrogers.com/salesforce-commerce-cloud-pricing-cost-of-ownership/
* Estimates for this sort of solution-set would start at about $300,000 annually
  * most likely be closer to $500,000 in the first year,
  * especially if fully managed and about $15,000 to 20,000 with a yearly service development container
  * Can be offset if Insight global were to become a salesforce redistributor AND/OR if the development services were partially staffed by Insight Global
  * Could do something like Shopify if desired, where the initial setup fees are much lower and the ability to integrate with sage ERP is much better initially, but the long term support costs associated with Ruby based devs is much higher
  * Also an option with Magento, but similar hurdles remain with costs up front, and PHP devs, but the added issue for payment processing. Really only a good choice if you need multiple skus from multiple warehouses and a plethora of B2B and B2C combination vendors/customers/clients
  
### Extra Resources for their Reading Pleasure 
_If team wants, can share to help them know where some info outside of head came from_
* Ubuntu Organizations - Enterprise
  * https://ubuntu.com/desktop/organisations
    * provides support even for physical servers
    * look into rpms to debs, binary ports available and plentiful
    * OR go the CentOS route
* Hostway - Louisville, KY Data Center
  * https://www.hosting.com/why-hosting/infrastructure/data-centers/louisville-kentucky-data-center/
        in their main space
        has security, cummins diesel, etc
        also known as Ntirety
* Cloud Scene to show current data center opportunities in Louisville, KY
  * https://cloudscene.com/market/data-centers-in-united-states/louisville-ky
* Kentucky Research Data Center, collab between UK and US Census Bureau
  * http://krdc.uky.edu/
* Flexential, Another Data Center Service Provider with KY Stats
  * https://www.flexential.com/data-centers/kentucky
  * Colocation services: https://www.flexential.com/colocation/remote-hands
  * Data Protection and Recovery: https://www.flexential.com/data-protection/recovery-cloud-draas
  * Dedicated Cloud Servers: https://www.flexential.com/cloud/dedicated-servers
  * Managed Colocations: https://www.flexential.com/colocation/managed-colocation
* ERP Solutions for 2019: https://www.webopedia.com/TERM/E/ERP.html
* Difference between CRMs and ERPs: https://www.webopedia.com/DidYouKnow/Hardware_Software/the-difference-between-crm-and-erp.html
  * ERP Buyers Guide for Small Businesses: http://www.enterpriseappstoday.com/erp/small-business-erp-buyers-guide-1.html
  * Salesforce: CRM, ERP and MDM: https://www.salesforce.com/video/1757878/
  * Salesforce: Consumer Goods Suggestion: https://www.salesforce.com/products/consumer-goods-cloud/overview/
  * Salesforce: Consumer Goods Suggesions: https://www.salesforce.com/solutions/industries/consumer-goods/overview/
  * Salesforce: Consumer Goods Cloud Customer Testimonials: https://www.salesforce.com/solutions/industries/consumer-goods/customer-stories/
* Universities in that Area of Paducah:
  * Gideon Roberty University
  * West Kentucky Community & Technical
  * University of Kentucky: http://www.engr.uky.edu/research-faculty/departments/paducah-campus
    * Mechanical Engineering Students esp.
    * Engineering Students E-DAY community open house: http://www.engr.uky.edu/research-faculty/departments/paducah-campus/community-outreach/engineers-day-open-house
    * Co-OP placements are a requirement for these programs and internships
* Murray State University: https://www.murraystate.edu/
  * Agribusiness Economics SOA Program
  * Agriculltural Education SOA Program
  * Applied Engineering and Technology Management CSET Program
  * Career and Technical Education CEHS Programs
  * University of Illinoi Ext: https://extension.illinois.edu/
* Paducah Community Events: https://www.paducah.travel/event/this-month/
  * Community is a very engaged one, proud of their arts and culture awards this year especially, can get involved in this area too, with photography competitions and offerings on the farm that Yeiser Art Center can use for their 40+ year exhibition annually
  * Halloween and other holiday sponsored events on site
  * Get connected with the paducah travel websites, social media pages, etc


### Closing Remarks
> Lets go ahead and put something up on the calendar, to review with your current development teams, to ascertain the technical debt currently sitting with the company, so to mean what are the applications themselves actually doing, what payment processing gateways are required/non-negotiable and what kinds of services are being maintained in the legacy environments. That way we can asssess which direction is really needed, be it an all-in-one managed solution or a hybrid solution retaining some physical premise locations for the managed web/platform services

## Suggested Solutions Overview
---
_Emailed to Team_
* Presentation Medium: Slideshow
  * Motivated stakeholder who may not be aware of the details surrounding payment processing/software-specifics
  * Translates to an meeting closing with suggestion for second appointment scheduled on books to assess current technical debt
  * Definitely a lunch type of meeting that can be presented over a few slides on an iPad
* Strategy Highlights
  * Step 1: Connect with the local community on events highlighting farm, winning new UI/marketing assets in the process
    * activities taking advantage of Paducah's award winning art culture (esp landscape photography)
    * targeted campaigns/events for local residents per holidays (halloween farm events, etc)
    * emphasis on rentals, leases, and financing for equipment useful to local college students per move-ins, etc
    * brand ambassadors with UK students and Murray State (nations largest argicultural university)
  * Step 2: Improve stability of all platform SLAs via colocation AND/OR boxed-solution
    * take advantage of KYs lowest electricity costs in the US by over 20%
    * utilize datacenters off-set pricing via colocation with centers hosting UPS, Samsung, etc
    * remote management services offering solution-sets cheaper than current costs with RHEL licenses improperly utilized
    * Elimination of unpredicatable maintenance and development trigger dataloss
    * Increasing security and guaranteed uptime service availability to better than 99.997%
  * Step 3: Adopt a CRM and ERP integrated strategy, fostering better communication between inter-departmental teams, business to consumer and business to business partnerships
    * Improvement of inventory tracking via out-of-box platform and automated services
    * Improvement of business partner connected resources/web platforms to foster stable communication with firms like REI/BassPro, etc
    * Improvement of sales team communication throughout lead generation and sales performance pipeline
  * Step 4: Analysis of inventory movement, traffic/impressions via marketing and transaction processing GVM rates in quarters following steps 1-3
    * Using analysis of inventory movement to create stable sku management and product offering vision
    * Cohesive strategies between payment processors, GVM rates and transaction processing fees
    * Determination of UI, Customer Experience tracking software and colocation needs based on analysis (i.e. ShopifyPlus vs Magento vs Salesforce, etc)
* Overall recommendation in a nutshell:
  * Improve Commuity Engagement
  * Move to the Salesforce Commerce Goods Platform, encompassing the Sales Cloud, Marketing Cloud, Commerce Cloud, Service Cloud and Salesforce Platform
  * Run Infastructure through a Colocation and Remotely Managed Solution-Set so Edleman Farm Supply can focus more on what they do best, not DevOps
* Time and Cost Estimations
  * Step 1: 4-6 months depending on community season, discounts on merchandise per brand ambassadors, increase staffing by about 1-2% for farm locale
  * Step 2:
    * $350,000 to $500,000 and 6-12 months depending on integrations for boxed solution with annual $25,000 development service agreement
    * Starting at $400,000 for hybrid managed solution off-prem/cloud depending on transactions annually and 9-18 months depending on integrations
    * Reduction in costs of about 2-5% in low-pay-grade support personnel
    * Reduction in costs of about $3,000 annually per RHEL instance and about $1,200 annually per Windows Server instance retired for per solution
  * Step 3:
    * See step 2 for costs
    * Timing requires second meeting per technical debt, but could be as low as 6 months if using boxed-solution
  * Step 4:
    * Depends on stakeholders and associated board members comfort levels and projection/analysis schedule vs fiscal year
    * Internal Notes Regarding Synergy for Insight Global (not discussed with client)
    * Sourcing of low-pay-grade technical personnel would be reduced, but new customer service & sales rep needs could be an increase in staffing opportunities
    * Assissting client with process of becomming an official CO-OP/Internship sponsor with Murry State/UK, presents qualified leads for new applicant pools (graduates rated in top 30% of country)
    * Opportunity to leverage Salesforce affliate program, lending to higher margins at resale agreement & discounted rates for internal use
    * Opportunity to leverage whitelabeling of datacenter service agreement contracts and associated staffing requirements

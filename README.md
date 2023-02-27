# CMC Asset Manager (CAM)
## An approach and a set of code assets that enhance business user tooling thereby giving them an option to create and manage Assets in CMC.

Out of all the business tools shipped with HCL Commerce V9, Customer Management Center (CMC) is the most critical to business functions. It provides features to build Marketing content, setup promotions, manage categories and prodcuts, create page layouts, manageme installments to name a few. With the latest 9.1.x release HCL has even moved Scheduler, transport and account management to CMC which were previously a part of Administration tool.

Product management feature in CMC doesnt support creation of Assets. This means if you have an asset like a user manual pdf, image or a multimedia content it cannot be associated to the product via CMC.

This CMC Asset Manager (CAM) fills that gap by providing a set of files that can be easilty plugged in into LOBTools project giving business users a CMC menu option to create different types of assets and associate them with the product in CMC.

Product Manager, Marketing Manager or Category Manager can use the Assets tool to create assets like marketing image files, catalog image files, PDF documents, and multimedia files that can be used marketing campaigns.
The Asset can further by be mapped to a product through an attachment URL.

## Pre-requiites
- HCL Commerce v9 Development/ Runtime environment


## Installation Instructions

1. Download/clone the repository to your local development machine
2. Import CAM into LOBTools project in RAD/Eclipse workspace
   (This will override few files under LOBTools\WebContent and also create new ones)
3. Build the LOBTools project and restart server.
4. Launch CMC

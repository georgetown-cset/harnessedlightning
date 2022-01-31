# Raw Data Used in the Production of _Harnessed Lightning_

In the interest of transparency and research replicability, CSET is releasing the raw contract award data used in the production of its October 2021 report, “[Harnessed Lightning: How the Chinese Military is Adopting Artificial Intelligence](https://cset.georgetown.edu/publication/harnessed-lightning/).” This repository includes 343 notices of AI-related contracts awarded by the Chinese People’s Liberation Army and state-owned defense enterprises between April and November of 2020.

Each tender in CSET’s PLA procurement dataset includes seven variables taken directly from the contract: title, public_unit, information_type, content, created, deadline, and project_number. Wherever possible, the authors manually extracted another three fields from each tender’s content cell for use in the report’s analysis: end_user, supplier, and contract_value_RMB. All ten fields are listed below:

**title** - Each of 343 AI-related contracts in our dataset includes a title related to the system or equipment being purchased.

**public_unit** - Each contract also mentions an agency or department for which the tender is being filed, typically a large branch of an organization, such as “Strategic Support Force.” Official procurement records treat state-owned defense enterprises as extensions of the PLA, listing institutions like “China Aerospace Science and Technology Corporation” as purchasers.

**purchase_type** - Each contract in our dataset was awarded through either a competitive bidding (中标公告) or sole-source (单一来源公示; 单一来源公告) procurement process.
content - Each contract listed additional, detailed information in the body of the announcement text. Of the 343 AI-related contracts in our dataset, most included three specific pieces of information, which we manually extracted into additional columns for analysis:

**end_user** - The PLA unit or state-owned defense company that intended to use the technology, specified in 232 cases.

**supplier** - The company or research institution that successfully won the contract, specified in 331 cases. In contracts awarded by competitive bidding, the winner is typically denoted as “number one” (第一) among a list of two or three alternatives.

**contract_value_RMB** - The total value of the contract, specified in 205 cases.

**created** - The date the contract award notice was originally published.

**deadline** - Typically refers to the deadline for vendors to respond to a bid or protest a contract award.

**project_number** - A unique project identifying number, likely for internal use among PLA logistics officers or program managers, supplied only for some contracts in the dataset.

Please also note the following alterations made to the raw data:

For some fields, such as title and content, we have taken the liberty of adding a machine-translated version of the column for easier navigation by non-Chinese speakers. **These machine translations have a higher error rate than a skilled human translator. In particular, machine translation is poor at translating the names of Chinese entities—companies, universities, military organizations, etc.—and product names.**

In some cases, for reasons unknown to the authors, the People’s Liberation Army directly censored portions of content cells. This is typically denoted by a string of four or fewer “X”s in a content cell, as in “XXX.”

In other cases, CSET removed the contact information for individuals involved in the public procurement process in China. Telephone numbers and email addresses normally found in content cells have been replaced by a string of six or more “X”s, as in “XXXXXXXXXXX.” If you are a researcher or journalist in need of this information, please send a request to cset@georgetown.edu.

Finally, CSET also removed portions of content cells that expose the source of the data used in this analysis, or which direct users to potentially malicious third-party websites. This information has been replaced by a string of six or more “X”s, as in “XXXXXX.”

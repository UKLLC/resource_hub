# Partnering with UK LLC 

>Last modified: 07 May 2025
<div style="background-color: rgba(0, 178, 169, 0.3); padding: 10px; border-radius: 5px;">
This section provides information about partnering with UK LLC including, data flow diagrams and detailed sample text relating to UK LLC's processing of data.</div>

### UK LLC summary text: 

>UK Longitudinal Linkage Collaboration (UK LLC) is the national Trusted Research Environment (TRE) for the UK’s longitudinal research community. UK LLC collaborates with and supports Longitudinal Population Studies (LPS) by providing record linkage and TRE services; and supports the research community by providing external researchers with secure access to a research database of integrated data. 
>
>The purpose of the UK LLC Research Database is to host and process de-identified data from many UK Longitudinal Population Studies and to manage the linkage and integration of these data. Longitudinal Population Studies are studies that follow the lives of participant volunteers over time; often over whole lifetimes and generations of families. Data collected include biological samples, genomic data and in-depth and self-reported measures of health and wellbeing. LPS therefore provide unique insights into population health, behaviours and wellbeing. 
>
>The scientific opportunities of LPS are enhanced when participants’ data are collated and linked to their health and administrative data (e.g. education, employment, tax and benefits records) and environmental exposure data, and made available to authorised researchers to access via a single application process with distributive review to data owners. This provides a valued and unique resource for UK-based researchers and policy makers. Through this collaboration, LPS review each application for their linked-data and remain the decision-makers on whether to grant access.
> 
> **Aims of UK LLC:**
>
>The UK LLC is a ‘Trusted Research Environment’ (otherwise known as a ‘Secure Data Environment’), designed to link study data from major inter-disciplinary UK LPS participants, to a wide range of participants’ health and non-health records and other sources. The Trusted Research Environment is a set of technical and governance safeguards designed to protect data during research. Only de-identified data is held in the UK LLC, researchers can access data in the TRE but cannot remove it or take copies, and all users are thoroughly checked before access is provided under contract. The UK LLC TRE has public contributors involved across its design and operations, and is subject to independent audits by ethics panels, security experts and government auditors.
> 
>**The UK LLC has adopted the Five Safe’s principles:**
> * Safe data: data are de-identified to protect any confidentiality concerns. 
> * Safe projects: research projects are approved by UK LLC and each LPS and must be for the public good. 
> * Safe people: researchers using the UK LLC are trained and authorised to use data safely. 
> * Safe settings: the UK LLC TRE environment prevents unauthorised use. 
> * Safe outputs: screened and approved outputs that are non-disclosive. 
>
> The integrated data, infrastructure and accompanying governance aspects is collectively known as the UK LLC. 
> 
> The primary aim of the UK LLC is (1) to centrally facilitate the research programmes of all contributing studies (and those seeking to join). This includes studies which already operate as generic research databases and those which have a defined research theme which has been communicated with participants; and, (2) to provide an efficient access route to approved research users via mechanisms which uphold participants’ rights and expectations. 


## Data flow diagrams
![Data Flow Diagram](_static/split_file.jpg)
[**Figure 1**](_static/split_file.jpg) A high level overview of the data processing methodology used to flow data into the UK LLC TRE.

![Data Flow Diagram](_static/NHS_data.png)
[**Figure 2**](_static/NHS_data.jpg) Overview of data flow from data owner, National Health Service (NHS).

![Data Flow Diagram](_static/place_based_data_flow.png)
[**Figure 3**](_static/place_based_data_flow.jpg) Overview of data flow for place-based data linkage.

![Data Flow Diagram](_static/DataFlows1.png)
[**Figure 4**](_static/DataFlows1.jpg) Overview of indicative dataflow of ONS held datasets (Data 
owners: Department for Work and Pensions (DWP), HM Revenue 
and Customs (HMRC) and Department for Education (DfE))

### UK LLC data processing methodology text:

>A ‘split-file’ anonymisation process developed by Swansea University for the SAIL Databank is used to securely transfer all datasets from contributing LPS into the UK LLC TRE. In this methodology, the LPS data are split by LPS data managers into a file of personal identifiers and an externally meaningless ‘Link ID’ (File 1). Separately, the attribute data are de-identified (direct and pseudo identifiers are either dropped or transformed into less identifiable research variables) and indexed using the same ‘Link ID’ as the File 1 – this is called a File 2. 
>
>Importantly, this process restricts the handling and management of LPS participants’ personal identifiers to the contributing LPS, Digital Health and Care Wales (DHCW) (the UK LLC’s trusted third party/linkage broker) and the linked data owners and contracted geo-data modellers (including University of Leicester/City St George’s, University of London). This means no one party or organisation can see personal identifiers and participant data. Data integration and management is conducted by a dedicated UK LLC Data Team within the UK LLC TRE. 
>
>For more information on the UK LLC data processing methodology including the split file approach and linkage process, please refer to the [UK LLC Protocol](_static/UKLLC_Protocol_V2.1_CLEAN_14102024.pdf)


> [FAQs](https://ukllc.ac.uk/faq) about UK LLC


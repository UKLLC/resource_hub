# Partnering with UK LLC 

>Last modified: 09 Dec 2025
<div style="background-color: rgba(196, 214, 0, 0.3); padding: 10px; border-radius: 5px;">
This section provides information about partnering with UK LLC including, data flow diagrams and detailed sample text relating to UK LLC's processing of data.</div>

#### Text about UK LLC  

<details>
  <summary>UK LLC summary text</summary>

>UK Longitudinal Linkage Collaboration (UK LLC) is the national Trusted Research Environment (TRE) for the UK’s longitudinal research community. UK LLC collaborates with and supports Longitudinal Population Studies (LPS) by providing record linkage and TRE services; and supports the research community by providing external researchers with secure access to a research database of integrated data. 
>
>The purpose of the UK LLC Research Database is to host and process de-identified data from many UK Longitudinal Population Studies and to manage the linkage and integration of these data. Longitudinal Population Studies are studies that follow the lives of participant volunteers over time; often over whole lifetimes and generations of families. Data collected include biological samples, genomic data and in-depth and self-reported measures of health and wellbeing. LPS therefore provide unique insights into population health, behaviours and wellbeing. 
>
>The scientific opportunities of LPS are enhanced when participants’ data are collated and linked to their health and administrative data (e.g. education, employment, tax and benefits records) and environmental exposure data, and made available to authorised researchers to access via a single application process with distributive review to data owners. This provides a valued and unique resource for UK-based researchers and policy makers. Through this collaboration, LPS review each application for their linked-data and remain the decision-makers on whether to grant access.
</details>

<details>
  <summary>Aims of UK LLC</summary>

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
</details>

<details>
  <summary>Data processing methodology</summary>

>A ‘split-file’ anonymisation process developed by Swansea University for the SAIL Databank is used to securely transfer all datasets from contributing LPS into the UK LLC TRE. In this methodology, the LPS data are split by LPS data managers into a file of personal identifiers and an externally meaningless ‘Link ID’ (File 1). Separately, the attribute data are de-identified (direct and pseudo identifiers are either dropped or transformed into less identifiable research variables) and indexed using the same ‘Link ID’ as the File 1 – this is called a File 2. 
>
>Importantly, this process restricts the handling and management of LPS participants’ personal identifiers to the contributing LPS, Digital Health and Care Wales (DHCW) (the UK LLC’s trusted third party/linkage broker) and the linked data owners and contracted geo-data modellers (including University of Leicester/City St George’s, University of London). This means no one party or organisation can see personal identifiers and participant data. Data integration and management is conducted by a dedicated UK LLC Data Team within the UK LLC TRE. 
>
>For more information on the UK LLC data processing methodology including the split file approach and linkage process, please refer to the [UK LLC Protocol](https://doi.org/10.5281/zenodo.10868638)
</details>

#### Data flow diagrams

<details>
  <summary>Overview</summary>

![Data Flow Diagram](_static/split_file.jpg)
[**Figure 1**](_static/split_file.jpg) A high level overview of the data processing methodology used to flow data into the UK LLC TRE.
</details>

<details>
  <summary>Health record linkage</summary>

![Data Flow Diagram](_static/NHS_data.jpg)
[**Figure 2**](_static/NHS_data.jpg) Overview of data flow from data owner, National Health Service (NHS).
</details>

<details>
  <summary>Place-based data linkage</summary>

![Data Flow Diagram](_static/place_based_data_flow.jpg)
[**Figure 3**](_static/place_based_data_flow.jpg) Overview of data flow for place-based data linkage.
</details>

<details>
  <summary>Administrative record linkage</summary>

![Data Flow Diagram](_static/DataFlows1.jpg)
[**Figure 4**](_static/DataFlows1.jpg) Overview of indicative dataflow of ONS held datasets (Data 
owners: Department for Work and Pensions (DWP), HM Revenue 
and Customs (HMRC) and Department for Education (DfE))
</details>

#### Study Zones

***This section is designed for UK LLC partner Longitudinal Population Studies***

<details>
  <summary>What is a Study Zone?</summary>
A Study Zone is a dedicated space within the UK LLC Trusted Research Environment (TRE) for each partner Longitudinal Population Study (LPS).    
</details>

<details>
  <summary>What analyses will I be able to do in my Study Zone?</summary>

In a Study Zone, you can only conduct quality checks, curation and methodological enhancement. You must not do any applied research in your Study Zone. If you want to conduct an applied research project, you’ll need to submit an Expression of Interest (EoI) – for instructions, see [UK LLC Guidebook: How do I apply?](https://guidebook.ukllc.ac.uk/docs/ukllc_key_facts/applying/intro)   
</details>

<details>
  <summary>When can I access my Study Zone?</summary>

You will only be able to access your Study Zone once it has been set up by UK LLC (see below), you have deposited at least one File 2 and your participants have been linked to e.g. NHS England.      
</details>

<details>
  <summary>Who should have access to my Study Zone?</summary>
  
Only the people in your team who are going to be working on the data in the Study Zone within the UK LLC TRE need to have access. Only Office for National Statistics (ONS) [Accredited Researchers](https://www.ons.gov.uk/aboutus/whatwedo/statistics/requestingstatistics/secureresearchservice/becomeanaccreditedresearcher) can access the UK LLC TRE – all members of your team will therefore need to attain accreditation prior to access.        
</details>

<details>
  <summary>I am a new partner LPS – how can I set up my Study Zone?</summary>

**Please follow the steps below to request help from UK LLC to set up your Study Zone:**

- Email access@ukllc.ac.uk with the names and email addresses of the LPS team members who will need to access the Study Zone (only include your LPS’s Principal Investigator if they will actually be working on the data). Please specify the team lead and include contact details for the contracts department in your organisation so that we can negotiate the signing of a Data Access Agreement (DAA).   

- When you’ve supplied the information above, the UK LLC Applications Team will complete your application for you (for Study Zones you don’t need to complete an Expression of Interest).  

- Each LPS team member named on the application will receive an automated email from UK LLC inviting them to set up an account in UK LLC Apply. This lets each team member see all the information about their application and enables them to provide the information detailed in step 4 and fulfil the project governance requirements detailed in step 5. It is therefore mandatory that you set up an account.  

- Once you’ve set up your account, log into UK LLC Apply and complete the section about information security policy and practice at your organisation. You need to specify if your organisation holds either ISO 27001 certification or [NHS England Data Security & Protection Toolkit](https://www.dsptoolkit.nhs.uk/organisationsearch) that covers the scope of your LPS team (please include the relevant reference number). If your organisation holds neither of these assurances, please write none and you will be asked to sign a different type of contract with UK LLC called a System Level Security Policy. See [UK LLC Guidebook: complete your project governance](https://guidebook.ukllc.ac.uk/docs/ukllc_key_facts/applying/paperwork) for further information.  

- In UK LLC Apply each team member must accept the UK LLC Data User Responsibilities Agreement (DURA) and the project-specific Data Owners’ Terms and Conditions (e.g. NHS England).   

- Once all project governance steps have been fulfilled, i.e. Data Access Agreement, DURA, Data Owners’ Ts&Cs and we’ve verified your ONS Accredited Researcher status, we will provision data to your Study Zone. You will receive an automated email from UK LLC explaining how to log into the UK LLC TRE and get started. See the [UK LLC Guidebook: TRE User Guide](https://guidebook.ukllc.ac.uk/docs/user_guide/introduction) for further information.         
</details>



> [FAQs](https://ukllc.ac.uk/faq) about UK LLC


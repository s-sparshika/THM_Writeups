# MISP - MALWARE INFORMATION SHARING PLATFORM
![image](https://github.com/s-sparshika/THM_Writeups/assets/68326118/8b36e4ac-0634-41f3-be5f-2196475dee1a)
## Task -2 
## What is MISP?
MISP (Malware Information Sharing Platform) is an open-source threat information platform that facilitates the collection, storage and distribution of threat intelligence and Indicators of Compromise (IOCs) related to malware, cyber attacks, financial fraud or any intelligence within a community of trusted members. 
Information Sharing - Public, NIDS , SIEM

### MISP effectively useful for the following use cases:
- Malware Reverse Engineering
- Security Investigations
- Intelligence Analysis
- Law Enforcement
- Risk Analysis
- Fraud Analysis

### What does MISP support?
![image](https://github.com/s-sparshika/THM_Writeups/assets/68326118/5588af31-f212-4ddd-a92b-bb3c033d1334)
- IOC database
- Automatic Correlation
- Data Sharing
- Import and Export Features
- Event Graph
- API support

  ## Task-3
## Dashboard:
   Provides functionalities to track, share and correlate events and IOCs identified during your investigation.
    ![image](https://github.com/s-sparshika/THM_Writeups/assets/68326118/6233c78b-3738-4c55-a2c4-8193886b50a7)
- Home button
- Event Actions
- Event Actions
- Dashboards
- Galaxies
- Input Filters
- Global Actions
- MISP
- Name
- Envelope
- Log out
  
## Event Management:
  As an analyst, will create all malware investigation correlations by providing descriptions and attributes associated with the investigation. Splitting the process into three significant phases, we have: 
- Event Creation.
- Populating events with attributes and attachments.
- Publishing.

## Event Creation:
  Events are a storage of general information about an incident or investigation. We add the description, time, and risk level deemed appropriate for the incident by clicking the Add Event button. Additionally, we specify the distribution level we would like our event to have on the MISP network and community. According to MISP, the following distribution options are available:
  - Your organization only
  - This community-only
  - Connected Communities
  - All Communities

## Attributes & Attachments:
  Feeds contains indicators i.e imported into MISP and information on security events. provide analysts and organisations with continuously updated information on threats and adversaries and aid in their proactive defence against attacks.
  -  MISP Feeds provide a way to:
      - Exchange threat information.
      - Preview events along with associated attributes and objects.
      - Select and import events to your instance.
      - Correlate attributes identified between events and feeds.
- Are enabled and managed by 'Site Admin' - analysts to obtain information on events and indicators.

## Taxonomies:
  Means of classifying information based on standard features or attributes. On MISP, taxonomies are used to categorise events, indicators and threat actors based on tags that identify them.
![image](https://github.com/s-sparshika/THM_Writeups/assets/68326118/eff0deb7-8cd8-4fc9-900f-a260a9a66248)

- Set events for further processing by external tools such as VirusTotal.
Ensure events are classified appropriately before the Organisation Admin publishes them.
Enrich intrusion detection systems' export values with tags that fit specific deployments.

- Taxonomies are expressed in machine tags, which comprise three vital parts:
Namespace: Defines the tag's property to be used.
Predicate: Specifies the property attached to the data.
Value: Numerical or text details to map the property.

- These are listed under the Event Actions tab. The site admin can enable relevant taxonomies.

## Tagging:
  Information from feeds and taxonomies, tags can be placed on events and attributes to identify them based on the indicators or threats identified correctly. Allows effectvie sharing of threat information between users, communities and other organisations using MISP to identify various threats.
- Tags section
- Button represents global tags & local tags. ( Can add your unique tags to your MISP instance)

## Tagging at Event level vs Attribute Level
  Tags can be added to an event and attributes. Tags are also inheritable when set. It is recommended to set tags on the entire event and only include tags on attributes when they are an exception from what the event indicates. This will provide a more fine-grained analysis.
- The following tags can be considered a must-have to provide a well-defined event for distribution:
- Traffic Light Protocol: Provides a colour schema to guide how intelligence can be shared.
- Confidence: Provides an indication as to whether or not the data being shared is of high quality and has been vetted so that it can be trusted to be good for immediate usage.
- Origin: Describes the source of information and whether it was from automation or manual investigation.
- Permissible Actions Protocol: An advanced classification that indicates how the data can be used to search for compromises within the organisation.

## TASK 5
- What event ID has been assigned to the PupyRAT event?
  

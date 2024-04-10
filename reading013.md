Reading


What exactly is “Active Directory” and are the key services it provides?
Microsoft’s directory and identity management service is known as Active Directory (AD), operating predominantly in windows networks.

Key services: 
" Active Directory Domain Services (AD DS) – the core Active Directory service used to manage users and resources.
Active Directory Lightweight Directory Services (AD LDS) – a low-overhead version of AD DS for directory-enabled applications.
Active Directory Certificate Services (AD CS) – for issuing and managing digital security certificates.
Active Directory Federation Services (AD FS) – for sharing identity and access management information across organizations and enterprises.
Active Directory Rights Management Services (AD RMS) – for information rights management (controlling access permissions to documents, workbooks, presentations, etc.) "

-Direct quote taken from: https://www.cyberark.com/what-is/active-directory/


What are the differences between a domain, forest, and tree in Active Directory?
They can be differentiated in the following ways:
" A domain is a collection of objects (e.g. users, devices) that share the same Active Directory database. A domain is identified by a DNS name like company.com.
A tree is a collection of one or more domains with a contiguous namespace (they have a common DNS root name like marketing.company.com, engineering.company.com, and sales.company.com).
A forest is a collection of one or more trees that share a common schema, global catalog, and directory configuration—but aren’t part of a contiguous namespace. The forest typically serves as the security boundary for an enterprise network. "

-Direct quote taken from: https://www.cyberark.com/what-is/active-directory/


How can objects (e.g. users, devices) within a domain be grouped?
" Objects within a domain can be grouped into organizational units (OUs) to simplify administration and policy management. Administrators can create arbitrary organizational units to mirror functional, geographical, or business structures, and then apply group policies to OUs to simplify administration. "

-Direct quote taken from: https://www.cyberark.com/what-is/active-directory/

Explain the benefits of Active Directory, as you would to a family member.
The good news is that Active Directory is a centralized system...the bad news is that Active Directory is a centralized system. It is practical in real life, more secure, simple to manage and resilient. However, as a centralized system, one breach and the crooks have the keys to the whole domain.  It's a bit like the Death Star, a tough nut to crack, virtually impregnable yet one weakness leaves it prone to black swan events that everyone will hear of and focus on. 


## Things I want to know more about

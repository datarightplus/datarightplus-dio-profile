%%%
title = "DataRight+: Australian DataRight+ Profile"
area = "Internet"
workgroup = "datarightplus"
submissionType = "independent"

[seriesInfo]
name = "Internet-Draft"
value = "draft-authors-datarightplus-dio-profile-latest"
stream = "independent"
status = "experimental"

date = 2024-04-03T00:00:00Z

[[author]]
initials="S."
surname="Low"
fullname="Stuart Low"
organization="Biza.io"
[author.address]
email = "stuart@biza.io"

%%%

.# Abstract

This is the ecosystem profile for the Australian DataRight+ deployment, an extension upon the Australian Consumer Data Right. This specification seeks to extend, in a non-conflicting way, [@!PROFILE-AU-CDR] to enhance the functionality within the Australian ecosystem.

.# Notational Conventions

The keywords "**MUST**", "**MUST NOT**", "**REQUIRED**", "**SHALL**", "**SHALL NOT**", "**SHOULD**", "**SHOULD NOT**", "**RECOMMENDED**",  "**MAY**", and "**OPTIONAL**" in this document are to be interpreted as described in [@!RFC2119].

{mainmatter}

# Scope

The scope of this document is intended to combine the extensions created as part of the DataRight+ initiative into a profile that sits upon the baseline context of the Australian CDR, ostensibly described in [@!PROFILE-AU-CDR].

# Terminology

This specification utilises the various terms outlined within [@!DATARIGHTPLUS-ROSETTA].

# Providers

In addition to complying with the relevant provisions in [@!PROFILE-AU-CDR] Providers:

1. **MUST** make available a discovery document as outlined in [@!DATARIGHTPLUS-DISCOVERY];
2. **MUST** support, where appropriate, the provisions outlined in [@!DATARIGHTPLUS-VERSIONING];
3. **MAY** support the provisions outlined [@!BULK-BANKING-TX-DETAIL];

# Initiators

In addition to complying with the relevant provisions in [@!PROFILE-AU-CDR] Initiators:

1. **MUST** support Enhanced Versioning as outlined in [@!DATARIGHTPLUS-VERSIONING];
2. **MUST** utilise the Provider discovery document as outlined in [@!DATARIGHTPLUS-DISCOVERY];
3. **MAY** support accessing the Banking Transaction Detail List as specified by [@!BULK-BANKING-TX-DETAIL]

# Acknowledgement

The following people contributed to this document:

- Stuart Low (Biza.io) - Editor

{backmatter}

<reference anchor="CDR-RULES" target="https://www.legislation.gov.au/F2020L00094/2023-07-22/text"> <front><title>Competition and Consumer (Consumer Data Right) Rules 2020</title><author><organization>Department of the Treasury</organization></author></front> </reference>

<reference anchor="PROFILE-AU-CDR" target="https://datarightplus.github.io/datarightplus-cdr-profile/draft-authors-datarightplus-cdr-profile.html"> <front><title>DataRight+: Australian CDR Profile</title><author initials="S." surname="Low" fullname="Stuart Low"><organization>Biza.io</organization></author></front> </reference>

<reference anchor="DATARIGHTPLUS-ROSETTA" target="https://datarightplus.github.io/datarightplus-rosetta/draft-authors-datarightplus-rosetta.html"> <front><title>DataRight+ Rosetta Stone</title><author initials="S." surname="Low" fullname="Stuart Low"><organization>Biza.io</organization></author></front> </reference>

<reference anchor="DATARIGHTPLUS-DISCOVERY" target="https://datarightplus.github.io/datarightplus-discovery/draft-authors-datarightplus-discovery.html"> <front><title>DataRight+: Discovery</title><author initials="S." surname="Low" fullname="Stuart Low"><organization>Biza.io</organization></author></front> </reference>

<reference anchor="DATARIGHTPLUS-ENHANCED-VERSIONING" target="https://datarightplus.github.io/datarightplus-enhanced-versioning/draft-authors-datarightplus-enhanced-versioning.html"> <front><title>DataRight+: Enhanced Endpoint Versioning</title><author initials="S." surname="Low" fullname="Stuart Low"><organization>Biza.io</organization></author></front> </reference>





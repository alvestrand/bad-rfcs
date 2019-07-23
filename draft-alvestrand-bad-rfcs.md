---
title: Bad RFCs
abbrev: bad-rfcs
docname: draft-alvestrand-bad-rfcs
category: info

ipr: trust200902
area: General
workgroup: None
keyword: Internet-Draft

stand_alone: yes
pi: [toc, sortrefs, symrefs]

author:
 -
    ins: "H. Alvestrand"
    name: "Harald Tveit Alvestrand"
    organization: "Google"
    email: harald@alvestrand.no

normative:
  RFC2119:

informative:
  RFC1:
  RFC1796:



--- abstract

This document seeks to show that the problem with the RFC series is that
there are not enough bad RFCs.

--- middle

# Introduction

Over the last twenty years (at least), a debate has raged in the IETF community
over the proper role of the RFC series.

This memo argues the position that the RFC series has a historical purpose as a
repository of information about the thinking of people that made the Internet
run, and that many of the issues we see with the way the series is treated today
can be mitigated or resolved by making sure we have more RFCs that the community
acknowledges as "bad RFCs".

# Conventions and Definitions

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD",
"SHOULD NOT", "RECOMMENDED", "NOT RECOMMENDED", "MAY", and "OPTIONAL" in this
document are to be interpreted as described in BCP 14 {{RFC2119}} {{!RFC8174}}
when, and only when, they appear in all capitals, as shown here.

# Extreme positions in the RFC debate

## All RFCs are considered standards, therefore they should be

Despite the protestations of {{RFC1796}} ("Not all RFCs are standards"), and the
fact that {{RFC1}} ("Host software") is not a standard by any stretch of the
imagination, the claim is often made that "the marketplace considers all RFCs to
be standards, and therefore anything that is not either a standard or approved
by IETF consensus as standards-equivalent should not be published in the RFC
series".

The most cited anecdote to support this position is probably the story from
approximately 2000 when a salesperson asked an engineer for a list of standards
that their product supported, and the engineer included {{RFC1149}} ("A Standard
for the Transmission of IP Datagrams on Avian Carriers") in the list as a joke,
and the salesman didn't discover the joke before the relevant publication (which
expanded the RFC numbers to include their titles) had already been printed.

Holders of this extreme position would claim that the anecdote shows that the
publication of RFC 1149 was a Bad Thing.

### Consequences of the "all RFCs should be standards" position

The logial consequence of this is that one has to install a single arbiter of
RFC publication (with the IESG usually proposed for that role), with strict
rules about what can and cannot be published, and refusal being the default
position whenever there is doubt.

This also entails closing down the independent submission series, the use of the
RFC series for IAB workshop reports and IETF procedural documents, and the
publication of April 1 RFCs.

What to do about the existing RFC documents, with its embarassingly variable
content, is then a conundrum; the most extreme position one could imagine would
be to institute official denial that certain RFCs ever existed, but that's
hardly likely to be a viable option.

## RFCs are postings in a slow-running debate, and that's what they should be

This extreme position argues that the RFC series has traditionally been an
invitation to debate, a publication where ideas got presented, and a permanent
record of those deliberations.

### Consequences of the "RFCs are postings" position

The logical consequence of this position is to emphasize speedy production of
RFCs, so that the information in there remains relevant; the current frequent
occurence of multi-year "holds" on publication because of formal issues (most
commonly reference errors) is then seen as an aberration of the process, not a
feature.


# Evidence to be considered

# Conclusion

# Security Considerations

The debate over the proper role of the RFC series has consumed much energy that
would have been better spent improving Internet security. Therefore, the
continuation of that debate without properly expressed positions and application
of clear thinking based on facts is a danger to the security of the Internet.

Apart from that, security is not considered separately in this memo.


# IANA Considerations

This document has no IANA actions.



--- back

# Acknowledgments
{:numbered="false"}

TODO acknowledge.

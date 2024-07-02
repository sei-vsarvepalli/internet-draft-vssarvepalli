---
title: "IP Encapsulation within IP Protocol"
abbrev: IP-in-IP
docname: draft-ip-in-ip-protocol-latest
category: std
ipr: trust200902
workgroup: Network
keyword:
  - ip-in-ip
  - tunneling
  - rfc6169



author:
 -
    ins: V. Sarvepalli
    name: Vijay Sarvepalli
    email: vssarvepalli@cert.org



normative:

  RFC2003:
    display: IP-in-IP
  RFC6169:
    display: Tunneling Security Concerns

informative:





--- abstract

This document updates the {{?RFC2003}} that specifies a method by which an IP datagram may be
encapsulated (carried as payload) within an IP datagram with more detailed Security Considerations.
   Encapsulation is suggested as a means to alter the normal IP routing
   for datagrams, by delivering them to an intermediate destination that
   would otherwise not be selected by the (network part of the) IP
   Destination Address field in the original IP header.  Encapsulation
   may serve a variety of purposes, such as delivery of a datagram to a
   mobile node using Mobile IP.


--- middle

# Introduction



## Motivation




# Acknowledgments
{:numbered="false"}

The IETF QUIC Working Group received an enormous amount of support from many
people.

The compression design team did substantial work exploring the problem space and
influencing the initial draft version of this document.  The contributions of
design team members {{{Roberto Peon}}}, {{{Martin Thomson}}}, and
{{{Dmitri Tikhonov}}} are gratefully acknowledged.

The following people also provided substantial contributions to this document:

{:compact}
- <t>{{{Bence Béky}}}</t>
- <t>{{{Alessandro Ghedini}}}</t>
- <t>{{{Ryan Hamilton}}}</t>
- <t>{{{Robin Marx}}}</t>
- <t>{{{Patrick McManus}}}</t>
- <t>{{{Kazuho Oku}{奥 一穂}}}</t>
- <t>{{{Lucas Pardue}}}</t>
- <t>{{{Biren Roy}}}</t>
- <t>{{{Ian Swett}}}</t>

This document draws heavily on the text of {{!RFC7541}}.  The indirect input of
those authors is also gratefully acknowledged.

{{{Buck Krasic}}}'s contribution was supported by Google during his employment
there.

A portion of {{{Mike Bishop}}}'s contribution was supported by Microsoft during
his employment there.

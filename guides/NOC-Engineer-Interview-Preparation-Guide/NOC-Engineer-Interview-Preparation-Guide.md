NOC ENGINEER

INTERVIEW PREPARATION GUIDE

108 real-world scenarios for Network Operations Center interviews, from
your first NOC role to senior escalation

First edition

By

Jiwan Bhattarai

IT Education Nepal

# Publication Details

**NOC Engineer Interview Preparation Guide: 108 Real-World Scenarios
from L1 to L3**

First edition, September 2026. This edition consolidates the NOC
Engineer Interview Scenarios collection into a single book. It adds a
full technical and editorial review, tier data, cross-referenced
appendices and a new appendix of peer-reviewed research.

Author: Jiwan Bhattarai, CCIE #60261, CEH. Published by IT Education
Nepal.

How to cite: J. Bhattarai, *NOC Engineer Interview Preparation Guide:
108 Real-World Scenarios from L1 to L3*, 1st ed. IT Education Nepal,
2026.

[]{#feedback .anchor}**Feedback and corrections.** Write to
contact@iteducationnepal.org. Include the scenario number, the platform
and software version, the command, the expected result and the actual
result. Vendor behaviour changes between releases, so a precise report
helps the next reader. Corrections that add a primary standard reference
are especially valued. A suggested new scenario should include a way to
verify it.

**Licence.** This work is licensed under the Creative Commons
Attribution 4.0 International Licence (CC BY 4.0). You may copy,
redistribute, adapt and build upon it for any purpose, including
commercially, provided you give appropriate credit, provide a link to
the licence, and indicate whether changes were made. Full licence text:
https://creativecommons.org/licenses/by/4.0/

Suggested attribution: *"NOC Engineer Interview Preparation Guide" by
Jiwan Bhattarai, IT Education Nepal, licensed under CC BY 4.0.*

The licence covers the text of this book. It does not cover the
standards, papers and vendor documents referenced in it, which remain
the property of their publishers. It grants no rights in any trademark.

**Trademarks.** Cisco, Cisco IOS, IOS XE, Catalyst, ASA and Packet
Tracer are trademarks or registered trademarks of Cisco Systems,
Inc. Palo Alto Networks and PAN-OS are registered trademarks of Palo
Alto Networks, Inc. Fortinet and FortiGate are registered trademarks of
Fortinet, Inc. Juniper Networks and Junos are registered trademarks of
Juniper Networks, Inc. Amazon Web Services and AWS are trademarks of
Amazon.com, Inc. or its affiliates. Microsoft, Windows, Windows Server,
Exchange and Azure are trademarks of the Microsoft group of companies.
Google Cloud is a trademark of Google LLC. Linux is the registered
trademark of Linus Torvalds. Red Hat and RHEL are trademarks of Red Hat,
Inc. Ubuntu is a registered trademark of Canonical Ltd. Wireshark is a
registered trademark of the Wireshark Foundation. Fluke is a registered
trademark of Fluke Corporation. ITIL is a registered trademark of
PeopleCert group. GNS3 is a trademark of GNS3 Technologies Inc. EVE-NG
is a trademark of EVE-NG Ltd. All other marks belong to their owners.

**Disclaimer.** This is an independent educational work. It is not
official courseware, and it is not endorsed by or affiliated with any
vendor or organisation named in it. The scenarios are illustrative.
Addresses, hostnames and credentials are examples only. Commands were
written against the platforms listed under [Review status and tested
platforms](#review-status-and-tested-platforms). Syntax and defaults
vary by release, so verify every command in your own environment and
respect the safety label on each command block before using it on a
production device. The author and publisher accept no liability for loss
or disruption arising from the use of this material.

# Mission and Motivation

**Learn how to learn. Learn by doing.**

**Let us create 10,000 quality IT engineers, from Nepal to the world.**

Jiwan Bhattarai

CCIE #60261 \| CEH \| Mentor \| Education Activist

## About IT Education Nepal

IT Education Nepal (ITEN), कम्प्युटर शिक्षा सबैका लागि (Computer education
for all)

IT Education Nepal is a volunteer-driven, non-profit initiative
providing practical computer education to Nepali speakers around the
world. It was founded on the principle that technology literacy is a
universal right, and it works to remove the geographic, language and
financial barriers that keep many learners out of IT education.

Many learners finish formal study with strong theory and very little
practice in the skills the job actually asks for. ITEN exists to close
that gap.

Let us learn and grow together. संगै सिकौं, संगै बढौं!

  -----------------------------------------------------------------------
  Channel                 Link
  ----------------------- -----------------------------------------------
  Website                 iteducationnepal.org

  YouTube                 www.youtube.com/@iteducationnepal

  GitHub                  github.com/ITEN-Non-Profit

  LinkedIn                www.linkedin.com/company/iteducationnepal

  Facebook community      www.facebook.com/groups/iteducationnepal

  Telegram                t.me/iteducationnepal
  -----------------------------------------------------------------------

## About the Author

Jiwan Bhattarai holds the Cisco Certified Internetwork Expert (CCIE
#60261) and Certified Ethical Hacker (CEH) certifications. He has worked
in the international IT industry and mentors students and early-career
engineers on technical skill and career growth.

He founded IT Education Nepal with one goal: develop 10,000 skilled IT
engineers from Nepal for the global market. His teaching joins technical
practice with mindfulness, an approach he calls "where technology meets
tranquility."

LinkedIn:
[www.linkedin.com/in/jiwanbhattarai](http://www.linkedin.com/in/jiwanbhattarai)

# Contents

[Publication Details](#publication-details) [2](#publication-details)

[Mission and Motivation](#mission-and-motivation)
[4](#mission-and-motivation)

[How to Use This Guide](#how-to-use-this-guide)
[7](#how-to-use-this-guide)

[Part I. Core Networking and
Services](#part-i.-core-networking-and-services)
[11](#part-i.-core-networking-and-services)

[Chapter 1. Routing and Switching](#chapter-1.-routing-and-switching),
Q1 to Q14 [12](#chapter-1.-routing-and-switching)

[Chapter 2. DNS and DHCP](#chapter-2.-dns-and-dhcp), Q15 to Q22
[23](#chapter-2.-dns-and-dhcp)

[Part II. Security, Remote Access and
Wireless](#part-ii.-security-remote-access-and-wireless)
[31](#part-ii.-security-remote-access-and-wireless)

[Chapter 3. Firewall and Security](#chapter-3.-firewall-and-security),
Q23 to Q34 [32](#chapter-3.-firewall-and-security)

[Chapter 4. VPN and Remote Access](#chapter-4.-vpn-and-remote-access),
Q35 to Q41 [44](#chapter-4.-vpn-and-remote-access)

[Chapter 5. Wireless](#chapter-5.-wireless), Q42 to Q49
[51](#chapter-5.-wireless)

[Part III. NOC Operations](#part-iii.-noc-operations)
[59](#part-iii.-noc-operations)

[Chapter 6. Monitoring, Alerting and NOC
Process](#chapter-6.-monitoring-alerting-and-noc-process), Q50 to Q64
[60](#chapter-6.-monitoring-alerting-and-noc-process)

[Part IV. Cloud, Voice and the Physical
Layer](#part-iv.-cloud-voice-and-the-physical-layer)
[72](#part-iv.-cloud-voice-and-the-physical-layer)

[Chapter 7. Cloud and Load
Balancing](#chapter-7.-cloud-and-load-balancing), Q65 to Q72
[73](#chapter-7.-cloud-and-load-balancing)

[Chapter 8. VoIP and QoS](#chapter-8.-voip-and-qos), Q73 to Q78
[81](#chapter-8.-voip-and-qos)

[Chapter 9. Physical Layer and
Cabling](#chapter-9.-physical-layer-and-cabling), Q79 to Q84
[87](#chapter-9.-physical-layer-and-cabling)

[Part V. Escalation and Professional
Practice](#part-v.-escalation-and-professional-practice)
[93](#part-v.-escalation-and-professional-practice)

[Chapter 10. Escalation, ITIL and
Communication](#chapter-10.-escalation-itil-and-communication), Q85 to
Q91 [94](#chapter-10.-escalation-itil-and-communication)

[Part VI. Hosts, Supporting Protocols and
IPv6](#part-vi.-hosts-supporting-protocols-and-ipv6)
[101](#part-vi.-hosts-supporting-protocols-and-ipv6)

[Chapter 11. Server and OS
Networking](#chapter-11.-server-and-os-networking), Q92 to Q96
[102](#chapter-11.-server-and-os-networking)

[Chapter 12. Miscellaneous
Protocols](#chapter-12.-miscellaneous-protocols), Q97 to Q101
[108](#chapter-12.-miscellaneous-protocols)

[Chapter 13. IPv6](#chapter-13.-ipv6), Q102 to Q108
[114](#chapter-13.-ipv6)

Appendices

[Appendix A. Study Paths](#appendix-a.-study-paths)
[122](#appendix-a.-study-paths)

[Appendix B. Questions-Only Recall
Edition](#appendix-b.-questions-only-recall-edition)
[132](#appendix-b.-questions-only-recall-edition)

[Appendix C. Self-Assessment
Tracker](#appendix-c.-self-assessment-tracker)
[140](#appendix-c.-self-assessment-tracker)

[Appendix D. Command Reference](#appendix-d.-command-reference)
[142](#appendix-d.-command-reference)

[Appendix E. Ports, Protocols and
Markings](#appendix-e.-ports-protocols-and-markings)
[150](#appendix-e.-ports-protocols-and-markings)

[Appendix F. Standards Index](#appendix-f.-standards-index)
[156](#appendix-f.-standards-index)

[Appendix G. Research Foundations](#appendix-g.-research-foundations)
[163](#appendix-g.-research-foundations)

[Appendix H. Glossary](#appendix-h.-glossary)
[166](#appendix-h.-glossary)

[Appendix I. Corrections in This Edition](#appendix_i)
[171](#appendix_i)

# How to Use This Guide

Every scenario in this book is a question you might actually be asked,
or a fault you might actually be handed at 2 a.m. Each one gives you a
short answer you could say out loud in an interview, an explanation of
what is really happening underneath, the commands to confirm it, and a
link to the standard that governs the behaviour.

It is written to be read twice. The first time you will want the short
answers. The second time, with a lab open and a specific gap to close,
you will want the mechanism.

## Who it is for

**If you are new to networking**, start with the [L1 study
path](#a.1-l1-study-path-noc-analyst). Every chapter begins with a
plain-language orientation, and the L1 questions assume no more than
CCNA-level knowledge. You will not be thrown into BGP timers on page
one.

**If you already work in a NOC**, the [L2 study
path](#a.2-l2-study-path-noc-engineer) is where the interview
differentiators live. You probably know the symptoms already. What gets
you the job is explaining the mechanism when the interviewer asks "why?"
for the second time.

**If you are interviewing for senior or escalation roles**, the [L3
study path](#a.3-l3-study-path-senior-and-escalation-engineer) is short
on purpose. Senior interviews test judgement and protocol-level
reasoning more than recall, so those scenarios go deeper on fewer
things.

## Where to start

  -------------------------------------------------------------------------------------------
  I want to...                         Go to
  ------------------------------------ ------------------------------------------------------
  Follow a structured study route for  [Appendix A, Study Paths](#appendix-a.-study-paths)
  my level                             

  Go straight to a topic I am weak on  [Contents](#contents)

  Test myself without seeing answers   [Appendix B, Questions-Only Recall
                                       Edition](#appendix-b.-questions-only-recall-edition)

  Score my readiness honestly          [Appendix C, Self-Assessment
                                       Tracker](#appendix-c.-self-assessment-tracker)

  Look up a command, a port or a       [Appendices D, E and
  standard                             F](#appendix-d.-command-reference)

  Read the research behind the         [Appendix G, Research
  mechanisms                           Foundations](#appendix-g.-research-foundations)
  -------------------------------------------------------------------------------------------

## How to study with this book

Reading this book front to back is the least useful way to use it. Three
methods, in order of value:

**1. Active recall, not recognition.** Use the [questions-only
edition](#appendix-b.-questions-only-recall-edition). Say your answer
out loud, in full sentences, as if the interviewer is sitting opposite
you. Then check.

Reading an answer and thinking "yes, I knew that" is recognition.
Recognition feels like knowledge and disappears the moment someone is
watching you. Recall is the thing that survives an interview.

**2. The "why" test.** For each scenario, try to explain the *What is
actually going on* part without looking. If you can name the cause but
cannot explain the mechanism, that is a gap.

Interviewers almost always follow up with "why?" once. Sometimes twice.
The first "why" separates people who memorised a list from people who
understand the protocol.

**3. Break it in a lab.** No book gives you the muscle memory of reading
a real interface counter during a live incident. Build the scenarios you
are weakest on and break them on purpose.

Free options include Containerlab (https://containerlab.dev/), GNS3
(https://www.gns3.com/), EVE-NG (<https://www.eve-ng.net/>) and Cisco
Packet Tracer (https://www.netacad.com/courses/packet-tracer). For
capture practice, the Wireshark sample captures
(https://wiki.wireshark.org/SampleCaptures) are free and immediately
useful.

This is the one gap no written guide closes, and it is the gap that
separates candidates who sound prepared from candidates who are
prepared.

## A note on the behavioural questions

[Chapter 10](#chapter-10.-escalation-itil-and-communication) covers
escalation, handover and stakeholder communication. Do not memorise
those answers. Interviewers hear textbook process answers constantly and
discount them immediately.

Take the principle, then rebuild the answer around an incident you
actually worked, using STAR: Situation, Task, Action, Result. Prepare
three or four real stories in advance and you can adapt them to almost
any behavioural question. A specific account of a real Friday night
outage beats a correct description of change management every single
time.

## Tier definitions

Interview expectations differ sharply by tier. Answering an L1 question
with L3 depth wastes everyone's time. Answering an L3 question with an
L1 answer ends the interview.

  ----------------------------------------------------------------------------
  Tier   Role         What is being tested       Answer shape
  ------ ------------ -------------------------- -----------------------------
  L1     NOC Analyst, Do you gather correct      Symptom recognition, correct
         Tier 1       data, follow the runbook,  first commands, knowing when
                      and escalate cleanly?      to hand off

  L2     NOC          Can you isolate a fault to Hypothesis, ordered
         Engineer,    a layer and a device       diagnostics, correct fix,
         Tier 2       without help?              rollback awareness

  L3     Senior,      Can you reason about       Mechanism-level explanation,
         Escalation   protocol behaviour and     packet-level evidence,
                      design the failure out?    permanent remediation
  ----------------------------------------------------------------------------

The 108 scenarios divide into 25 at L1, 73 at L2 and 10 at L3. [Appendix
A](#appendix-a.-study-paths) explains why the distribution looks like
that.

## Environment note

Where an answer changes between environments, the scenario says so. The
difference matters more than people expect:

- **Enterprise NOC.** You own the whole stack: access switches,
  wireless, firewalls, servers, users. Root cause is usually yours to
  find and yours to fix.
- **Service provider or ISP NOC.** You own transport and edge. Customer
  equipment is often out of scope, most escalations point toward transit
  or peering partners, and your instruments are BGP state, optical light
  levels and circuit IDs rather than endpoint troubleshooting.
- **MSP NOC.** Many small customers, hard contractual SLAs, constant
  context switching. Ticket hygiene and documentation are weighted as
  heavily as technical depth.

## Command safety labels

Every command block carries a label. Read it before you paste anything
into a production device.

  ------------------------------------------------------------------------------
  Label               Meaning
  ------------------- ----------------------------------------------------------
  read-only           Displays state. Safe on production.

  active test         Generates traffic or probes. Low risk, but visible in logs
                      and may trigger security alerts.

  service-affecting   Can interrupt traffic. Needs a maintenance window.

  change approval     Modifies configuration. Needs change control and a
                      rollback plan.
  ------------------------------------------------------------------------------

Debug commands are marked service-affecting even when they look
harmless, because debug output on a loaded control plane has taken
production routers down before.

## Anatomy of a scenario

Every scenario follows the same structure, so you always know where to
look.

  -----------------------------------------------------------------------
  Part            What it gives you
  --------------- -------------------------------------------------------
  Tier and Safety The interview level the question targets, and the most
                  disruptive command label in the scenario

  Short answer    What you could say out loud in the first thirty seconds

  What is         The mechanism, which is what the follow-up "why?" is
  actually going  testing
  on              

  How to check    Commands and procedures, each block marked with its
                  safety label

  Watch out for   The trap, the overlooked cause, or the detail that
                  lifts an answer

  References      The primary standard or vendor document that governs
                  the behaviour
  -----------------------------------------------------------------------

Scenarios in [Chapter
10](#chapter-10.-escalation-itil-and-communication) end with a STAR
prompt instead of a command block, because they test judgement and
experience rather than syntax.

## Review status and tested platforms

Last technical review: 25 July 2026.

Commands were written against the platforms below. Syntax and defaults
vary by release, so verify in your own environment before relying on
anything here in production.

  -----------------------------------------------------------------------
  Platform                          Tested against
  --------------------------------- -------------------------------------
  Cisco IOS / IOS XE                15.x, 17.x

  Cisco ASA                         9.x

  Cisco WLC / AireOS                8.x

  Linux                             Ubuntu 22.04, RHEL 9

  Windows Server                    2019, 2022

  AWS CLI                           v2
  -----------------------------------------------------------------------

Where a command is vendor-specific but has not been verified on a named
release, it is labelled a **command pattern** rather than presented as
exact syntax.

## Conventions

Placeholders appear in angle brackets, for example `<if>` for an
interface name and `<``ip``>` for an address. Replace them, brackets
included. Addresses in examples are illustrative, and none of them
belongs to a real network you should probe.

Scenario numbers run from Q1 to Q108 through the whole book, and
cross-references use those numbers, for example "see Q75". Spelling
follows British English. Protocol names, command syntax and the titles
of standards keep their original spelling.

# Part I. Core Networking and Services

Most NOC tickets begin as "I can't reach something", and most of those
turn out to be routing, switching or name resolution. Part I covers the
reasoning that settles those questions quickly: which layer is failing,
which device owns the fault, and what evidence proves it.

## Chapter 1. Routing and Switching

*Scenarios Q1 to Q14. Tier mix: 5 L1, 7 L2, 2 L3.*

### Orientation

Almost everything in a NOC starts here. When a user says "I can't reach
the server," you are being asked a routing and switching question
whether or not anyone uses those words.

Two ideas carry most of the weight:

**Switching happens inside a broadcast domain.** Devices in the same
VLAN talk to each other using MAC addresses. No router is involved, no
routing table is consulted.

**Routing happens between broadcast domains.** The moment the
destination is in a different subnet, the sending host gives up on
finding it directly, sends the frame to its default gateway, and a Layer
3 device takes over.

That single distinction is the first fork in most troubleshooting trees.
If something works inside a VLAN but not between VLANs, you have just
eliminated cabling, the NIC, and most of Layer 2 in one step.

### Scenarios in this chapter

  ----------------------------------------------------------------------------------------------------------------------------------------------------------------
  ID                                                                                               Scenario                                               Tier
  ------------------------------------------------------------------------------------------------ ------------------------------------------------------ --------
  [Q1](#q1.-a-user-cant-reach-a-server-in-another-vlan-but-can-reach-one-in-the-same-vlan)         Cross-VLAN reachability failure                        L1

  [Q2](#q2.-two-switches-show-a-spanning-tree-topology-change-every-few-minutes)                   Repeated STP topology changes                          L2

  [Q3](#q3.-after-adding-a-new-switch-users-report-intermittent-broadcast-storms)                  Broadcast storm after adding a switch                  L2

  [Q4](#q4.-a-route-works-via-traceroute-but-pings-drop-50-of-the-time)                            50% packet loss with working traceroute                L2

  [Q5](#q5.-ospf-neighbors-wont-form-between-two-routers-on-the-same-subnet)                       OSPF adjacency failure                                 L2

  [Q6](#q6.-a-newly-added-vlan-isnt-passing-traffic-across-a-trunk-link)                           VLAN not passing over a trunk                          L1

  [Q7](#q7.-users-on-one-floor-lose-connectivity-randomly-correlating-with-cleaning-staff-hours)   Time-correlated connectivity loss                      L1

  [Q8](#q8.-router-cpu-spikes-to-99-during-peak-hours)                                             Router control plane saturation                        L2

  [Q9](#q9.-a-static-route-works-for-one-subnet-but-not-its-neighbour-subnet)                      Static route covering one prefix only                  L1

  [Q10](#q10.-interface-counters-show-high-input-errors-and-crc-errors)                            CRC and input errors                                   L1

  [Q11](#q11.-users-behind-an-etherchannel-report-slow-throughput-despite-it-showing-up)           EtherChannel underperforming                           L2

  [Q12](#q12.-a-default-route-was-removed-accidentally-and-internet-access-failed-network-wide)    Preventing routing change outages                      L2

  [Q13](#q13.-a-bgp-peer-is-up-but-a-prefix-you-expect-is-missing)                                 BGP prefix not received or not installed               L3

  [Q14](#q14.-a-gateway-failover-didnt-happen-when-the-primary-router-failed)                      First-hop redundancy failure                           L3
  ----------------------------------------------------------------------------------------------------------------------------------------------------------------

### Q1. A user can't reach a server in another VLAN, but can reach one in the same VLAN

*Tier: L1. Safety: read-only.*

**Short answer.** Working inside the VLAN and failing across VLANs
points at Layer 3 or at policy. Check that a routed interface exists for
both VLANs and is up, that the client's gateway and subnet mask are
right, and that no ACL is blocking the flow in either direction.

Be careful how you phrase the reasoning. Same-VLAN success tells you the
NIC, the cable and the local switching path are working for *that* flow.
It does not prove the whole of Layer 2 is healthy, and it certainly does
not prove that policy for a different protocol and port is open.

**What is actually going on.** Traffic inside a VLAN is switched on MAC
address and never consults a routing table. Cross a subnet boundary and
the host has to ARP for its default gateway and hand the frame over to a
Layer 3 device. Several things can break that chain, and they produce
identical symptoms:

- The SVI or router subinterface is missing, shut down, or in
  line-protocol down state
- The subnet mask makes the host think the remote subnet is local, so it
  ARPs for a host that will never answer
- An ACL permits the return path but not the forward path, or vice versa
- The server's own gateway is wrong, so replies never come back

**How to check**

    Cisco IOS                                            [read-only]
      show ip interface brief | include Vlan
      show vlan brief
      show ip route <destination>
      show ip access-lists
      show run interface vlan <id>

    Client                                               [read-only]
      ipconfig /all                    Windows
      ip addr ; ip route               Linux
      arp -a                           is the gateway MAC resolving?

**Watch out for.** An SVI stays down until at least one access port in
that VLAN is up and the VLAN exists in the VLAN database. A freshly
configured VLAN with nothing plugged into it is the most common false
alarm here, and it catches people every time.

**References:** [IEEE
802.1Q](https://standards.ieee.org/ieee/802.1Q/10323/) · [RFC 826,
ARP](https://www.rfc-editor.org/rfc/rfc826.html)

### Q2. Two switches show a spanning-tree topology change every few minutes

*Tier: L2. Safety: read-only.*

**Short answer.** Something is flapping. Find the port that owns the
topology change with `show spanning-tree detail`, then look at that
port's flap history and error counters. Usual suspects are a failing
link, a duplex mismatch, or an edge port without PortFast.

**What is actually going on.** When a non-edge port moves into
forwarding, the switch floods a Topology Change Notification toward the
root bridge. The root sets the topology change flag, and every switch in
the domain shortens its MAC address table ageing time from 300 seconds
to the forward delay, typically 15 seconds.

The consequence is out of proportion to the cause. One flapping access
port produces network-wide unicast flooding, brief traffic loss and CPU
load. Ports facing end devices should carry PortFast so that a user
rebooting their PC does not generate a TCN at all.

**How to check**

                                                         [read-only]
    show spanning-tree detail | include ieee|occurred|from
    show spanning-tree interface <if> detail
    show interface <if> | include flap|error|duplex|reset
    show logging | include LINK-3|LINEPROTO

**Watch out for.** `show spanning-tree detail` names the last topology
change and the port it arrived on. Follow that port toward the source,
switch by switch. The flapping link is usually one or two hops away from
where you started looking.

**References:** [IEEE
802.1D](https://standards.ieee.org/ieee/802.1D/3268/) · [IEEE 802.1Q,
RSTP](https://standards.ieee.org/ieee/802.1Q/10323/)

### Q3. After adding a new switch, users report intermittent broadcast storms

*Tier: L2. Safety: read-only.*

**Short answer.** A forwarding loop. Either the new switch was cabled
with two uplinks into the same domain without STP converging properly, a
port was configured as access where it should trunk, or the switch
arrived with STP disabled or running an incompatible mode.

**What is actually going on.** Ethernet frames carry no TTL. A broadcast
that enters a loop is replicated forever, saturating links and CPU
within seconds, while MAC tables thrash because the same source address
keeps arriving on alternating ports.

STP exists to prevent this, but it can be defeated. The new switch may
run a different STP flavour. A port may be configured as an edge port
and then receive BPDUs. Somebody may have disabled STP on a VLAN to
"fix" a slow-linking port. BPDU Guard shuts an edge port that receives a
BPDU. Loop Guard stops a blocking port moving to forwarding when BPDUs
go quiet.

**How to check**

                                                         [read-only]
    show spanning-tree vlan <id>
    show spanning-tree inconsistentports
    show interface | include rate|drops        broadcast rate near 100%?
    show mac address-table | include <flapping mac>
    show logging | include MAC_MOVE|LOOP|BPDUGUARD

**Watch out for.** `%SW_MATM-4-MACFLAP_NOTIF` in the log, plus a MAC
address alternating between two ports, is a loop until proven otherwise.
Do not spend twenty minutes on other theories when that message is
sitting in the log.

**Reference:** [IEEE
802.1D](https://standards.ieee.org/ieee/802.1D/3268/)

### Q4. A route works via traceroute but pings drop 50% of the time

*Tier: L2. Safety: active test.*

**Short answer.** Two strong candidates. Either equal-cost multipath
where one of the two paths is broken or filtered, or a genuinely lossy
link. Run MTR from both ends and compare, then check interface error
counters along the suspect direction.

**What is actually going on.** Loss sitting close to a clean 50% is a
good hint at ECMP with one broken path. Traceroute keeps working because
it only needs one probe in three to come back per hop, which hides the
failure nicely.

Loss that varies randomly rather than sitting near 50% points somewhere
else: CRC errors, an oversubscribed link dropping from the tail of a
queue, or a failing optic. The distinction matters because one is fixed
in routing and the other needs someone with a ladder.

**How to check**

    Cisco IOS                                            [read-only]
      show ip route <dest>                    two next hops means ECMP
      show ip cef exact-route <src> <dest>
      show interface <if> | include errors|CRC|drops|input rate

    From a host                                          [active test]
      mtr -rwc 100 <dest>                     run from both ends
      hping3 -S -p 443 <dest>                 TCP test, not ICMP

**Watch out for.** ICMP is often rate-limited or deprioritised on router
control planes, so a router that drops your pings may be forwarding
transit traffic perfectly. Confirm with a TCP-based test before you tell
anyone there is an outage.

**References:** [RFC 792,
ICMP](https://www.rfc-editor.org/rfc/rfc792.html) · [RFC 6349, TCP
Throughput Testing](https://www.rfc-editor.org/rfc/rfc6349.html)

### Q5. OSPF neighbors won't form between two routers on the same subnet

*Tier: L2. Safety: read-only.*

**Short answer.** Work the checklist in order: same subnet and mask,
matching area ID, matching hello and dead timers, matching
authentication, matching MTU, matching stub flags, unique router IDs,
interface not passive, and no ACL blocking 224.0.0.5 and 224.0.0.6.

**What is actually going on.** The adjacency state tells you the cause,
which is why the mechanism matters more than the checklist.

  -----------------------------------------------------------------------
  Stuck at     Usual cause
  ------------ ----------------------------------------------------------
  Down / Init  Hellos are one-way. ACL, passive interface, or one side
               not sending.

  2-Way        Normal between two DROthers on a broadcast segment. Not a
               fault.

  ExStart /    Almost always MTU mismatch. Database Description packets
  Exchange     carry MTU and are rejected when it differs.

  Never forms  Mismatched hello or dead timers, area ID, or
  at all       authentication.
  -----------------------------------------------------------------------

**How to check**

                                                         [read-only]
    show ip ospf neighbor              the STATE names the problem
    show ip ospf interface <if>        area, timers, MTU, network type, auth
    show ip access-lists               permit 224.0.0.5 and 224.0.0.6

                                                         [service-affecting]
    debug ip ospf adj                  use with care on a busy router

**Watch out for.** Interviewers ask this often and expect the
state-to-cause mapping, not a recited parameter list. "Stuck in ExStart
means MTU" is the answer that separates an L2 candidate from an L1 one.

**Reference:** [RFC 2328, OSPF Version
2](https://www.rfc-editor.org/rfc/rfc2328.html)

### Q6. A newly added VLAN isn't passing traffic across a trunk link

*Tier: L1. Safety: read-only.*

**Short answer.** The VLAN is missing from the trunk's allowed list, not
created on one of the switches, pruned, or hit by a native VLAN
mismatch. Check both ends of the trunk, not just the one you configured.

**What is actually going on.** A trunk only carries VLANs in its allowed
list, and the VLAN has to exist and be active on both switches. Two
details catch people out repeatedly:

`switchport trunk allowed ``vlan`` 20` **replaces** the list. It does
not add to it. One mistyped command can black-hole every other VLAN on
that trunk, and it happens in production more often than anyone admits.

A native VLAN mismatch is worse than an outage. Untagged frames from one
side land in a different VLAN on the other, merging two broadcast
domains. That is a security problem and a loop risk rather than a clean
failure. CDP or LLDP logs it.

**How to check**

                                                         [read-only]
    show interface trunk           both ends, compare allowed and active
    show vlan brief
    show interface <if> switchport
    show logging | include NATIVE_VLAN_MISMATCH

**Watch out for.** Always use
`switchport trunk allowed ``vlan`` add <id>` on a production trunk. The
version without `add` is one of the most common causes of self-inflicted
trunk outages.

**Reference:** [IEEE
802.1Q](https://standards.ieee.org/ieee/802.1Q/10323/)

### Q7. Users on one floor lose connectivity randomly, correlating with cleaning staff hours

*Tier: L1. Safety: read-only.*

**Short answer.** Physical disturbance. Match interface flap timestamps
against the reported times, see which ports flap together, then inspect
cabling and any shared power outlet feeding a floor switch or media
converter.

**What is actually going on.** The time correlation does most of the
diagnostic work. When several ports on one switch flap together at a
repeating hour, the shared cause is usually power (an IDF switch plugged
into a socket a cleaner can reach) or physical (a patch cord under a
desk, a cable across a doorway).

One port flapping randomly is a cable or a NIC. Several ports flapping
in unison is something upstream: power, the uplink, or the switch
itself.

**How to check**

                                                         [read-only]
    show interface <if> | include last input|flapped|reset
    show logging | include LINK-3-UPDOWN
    show interface counters errors
    show power inline                          PoE devices resetting?
    show interface status err-disabled

**Watch out for.** Ask facilities before you ask engineering. A vacuum
cleaner sharing a circuit with an unprotected IDF switch is a real and
recurring root cause, and no amount of `show` output will ever reveal
it.

**Reference:** [ANSI/TIA Standards](https://tiaonline.org/)

### Q8. Router CPU spikes to 99% during peak hours

*Tier: L2. Safety: read-only.*

**Short answer.** Find the consuming process with
`show processes ``cpu`` sorted`, then work out whether the load is
punted traffic or genuine control plane work. Confirm hardware or CEF
switching has not fallen back to software.

**What is actually going on.** On a healthy router, transit traffic is
switched in hardware or by CEF and barely touches the CPU.

High CPU with high **interrupt** time means packets are being punted to
the CPU. Causes include an unsupported feature in the data path, an ACL
with `log` on a busy rule, IP options, fragmentation, TTL expiry from a
traceroute storm, or a TCAM that has overflowed and pushed forwarding
into software.

High CPU in a **named process** is control plane work instead: OSPF or
BGP recalculating after flaps, SNMP walking a large table, or NetFlow
export.

**How to check**

                                                         [read-only]
    show processes cpu sorted | exclude 0.00
    show processes cpu history          5-second, 1-minute, 72-hour graphs
    show ip cef                         is CEF enabled and populated?
    show ip traffic
    show controllers cpu-interface      punted packet counters

**Watch out for.** `show processes ``cpu`` history` is the fastest way
to prove the spike is periodic. A spike that lands on the same clock
minute every day is almost always a scheduled job: a backup, an SNMP
discovery sweep, or a vulnerability scanner.

**Reference:** [RFC 6192, Protecting the Router Control
Plane](https://www.rfc-editor.org/rfc/rfc6192.html)

### Q9. A static route works for one subnet but not its neighbour subnet

*Tier: L1. Safety: read-only.*

**Short answer.** A missing route or a wrong mask for the second prefix.
Check the routing table for the exact destination address rather than
reading the configuration and reasoning about it.

**What is actually going on.** Longest prefix match means a route for
10.1.1.0/24 tells you nothing at all about 10.1.2.0/24. The usual errors
are a /24 typed where the design called for a /23, a summary route that
does not actually cover the second subnet, or a next hop that has no
route of its own so the recursive lookup fails.

A static route pointing at an interface on a multi-access segment also
depends on proxy ARP, and fails quietly when proxy ARP is disabled.

**How to check**

                                                         [read-only]
    show ip route <specific destination ip>
    show ip route static
    show ip route <prefix> longer-prefixes
    ping <next-hop>                     is the next hop itself reachable?

**Watch out for.** Always test with the exact destination address.
`show ``ip`` route 10.1.2.15` returns the route that will actually be
used, which is a different question from what the config appears to say.

**Reference:** [RFC 1812, Requirements for IPv4
Routers](https://www.rfc-editor.org/rfc/rfc1812.html)

### Q10. Interface counters show high input errors and CRC errors

*Tier: L1. Safety: read-only.*

**Short answer.** Layer 1. CRC errors mean frames arrived corrupted: bad
cable, bad or dirty transceiver, interference, or a duplex mismatch.
Confirm speed and duplex match on both ends, then swap the cable and the
optic in that order.

**What is actually going on.** The counter pattern tells you which fault
you have:

  -----------------------------------------------------------------------
  Pattern         Likely cause
  --------------- -------------------------------------------------------
  CRC, no         Cable, connector, optic, or interference
  collisions      

  Late collisions Duplex mismatch. The full-duplex side transmits
  on one end, CRC whenever it likes. The half-duplex side counts late
  errors and      collisions; the full-duplex side counts CRC errors and
  runts on the    runts from the frames the half-duplex side abandoned.
  other           Compare the counters on both ends. Link light stays
                  green while throughput collapses.

  Input errors    Runts, giants, or framing problems. Often an MTU or
  without CRC     tagging mismatch.

  Rising          A cable that is failing rather than failed
  alignment       
  errors          
  -----------------------------------------------------------------------

**How to check**

                                                         [read-only]
    show interface <if>                 CRC, runts, giants, late collisions
    show interface <if> counters errors
    show interface <if> status          negotiated speed and duplex
    show interface transceiver detail   optical Tx and Rx in dBm

                                                         [read-only, resets counters]
    clear counters <if>                 then re-measure over a known window

**Watch out for.** Clear the counters before you draw conclusions. An
interface up for 400 days may be showing errors accumulated during an
incident someone fixed a year ago. Rate of increase matters. The total
does not.

**Reference:** [IEEE
802.3](https://standards.ieee.org/ieee/802.3/10422/)

### Q11. Users behind an EtherChannel report slow throughput despite it showing "up"

*Tier: L2. Safety: read-only.*

**Short answer.** Confirm every member link is actually bundled and
error-free, then look at the load-balancing hash. A bundle where one
member carries everything gives you single-link throughput no matter how
many members are up.

**What is actually going on.** A port channel does not stripe packets
across members. It hashes selected header fields to pick one member per
flow, which keeps packets in order but means a few large flows can all
land on the same link.

The default hash on many platforms is source MAC only, which is close to
useless when all traffic arrives via a router and therefore shares one
source MAC. Separately, LACP keeps a bundle "up" while individual
members are suspended for mismatched speed, duplex or VLAN config, and
one member with rising CRC errors drags the whole bundle down without
taking it offline.

**How to check**

                                                         [read-only]
    show etherchannel summary        flags: P bundled, s suspended, I individual
    show etherchannel load-balance
    show interface port-channel<n> | include rate
    show interface counters errors   compare members against each other
    test etherchannel load-balance interface po1 ip <src> <dst>

**Watch out for.** Flag `I` (individual) means a member is forwarding
outside the bundle. That is a loop risk, not just a performance problem.
Move the hash to `src-dst-ip` or `src``-``dst``-port` where the platform
supports it.

**Reference:** [IEEE 802.1AX, Link
Aggregation](https://standards.ieee.org/ieee/802.1AX/7404/)

### Q12. A default route was removed accidentally and internet access failed network-wide

*Tier: L2. Safety: change approval.*

**Short answer.** Three layers of defence. Change control with peer
review for any routing change. Redundancy so no single route deletion is
fatal, using a floating static or a dynamically learned default. And
configuration versioning so rollback takes seconds instead of
reconstruction from memory.

**What is actually going on.** The technical failure is trivial. The
process failure is the real answer.

Mature environments add configuration change logging so you can see
every command and who typed it, a pre-change snapshot, and a revert
timer where the platform supports one. Junos has `commit`` confirmed`.
IOS XE has `configure terminal revert timer`. Both undo the change
automatically if you lose access or forget to confirm, which is exactly
what happens when a change goes wrong.

**How to harden**

    Cisco IOS                                            [change approval]
      archive
        path <secure-transfer-target>
        write-memory
        log config
          logging enable
          notify syslog

      configure replace flash:pre-change.cfg force
      configure terminal revert timer 5      IOS XE

    Junos                                                [change approval]
      commit confirmed 5
      rollback 1

**Watch out for.** Do not back up configurations over TFTP. It has no
authentication and no encryption, and device configs contain SNMP
strings, pre-shared keys and hashed credentials. Use SCP, SFTP, or HTTPS
to an access-controlled store, and treat the backup repository as a
secret store rather than a file share.

In a service provider environment the default route usually arrives via
BGP, so the equivalent mistake is a mis-scoped route-map or prefix-list
rather than a deleted static. The remediation is identical.

**References:** [ITIL 4 Change
Enablement](https://www.axelos.com/certifications/itil-service-management)
· [RFC 4271, BGP-4](https://www.rfc-editor.org/rfc/rfc4271.html)

### Q13. A BGP peer is up, but a prefix you expect is missing

*Tier: L3. Safety: read-only.*

**Short answer.** Establish where the prefix stops. Is the neighbour
sending it, are you receiving it, are you accepting it after inbound
policy, and is it winning best-path selection? Those are four different
failures and each has a different fix.

**What is actually going on.** "The peer is up" only means the TCP
session and the BGP finite state machine reached Established. Everything
interesting happens after that.

Walk it in order:

1.  **Is it being advertised?** The neighbour's outbound policy may
    filter it, or they may not have it in their table either.
2.  **Is it arriving?**
    `show ``bgp`` ``neighbor`` <``ip``> ``received-routes` needs soft
    reconfiguration inbound or route refresh, otherwise you are looking
    at post-policy routes and drawing the wrong conclusion.
3.  **Is inbound policy dropping it?** A prefix-list, route-map, AS-path
    filter, or an ORF can silently discard it.
4.  **Did it lose best-path?** It may be in the BGP table but not the
    RIB, beaten by a shorter AS path, higher local preference, or a
    lower-origin route from elsewhere.
5.  **Is the next hop reachable?** A prefix with an unresolvable next
    hop is valid but never installed. This one catches people constantly
    in iBGP designs without next-hop-self.
6.  **Did you hit max-prefix?** Some implementations warn and keep
    going; others tear the session down. Check the log.

**How to check**

                                                         [read-only]
    show bgp ipv4 unicast summary
    show bgp neighbor <ip> received-routes      needs soft-reconfig or refresh
    show bgp neighbor <ip> routes               post-policy
    show bgp neighbor <ip> advertised-routes    what you send them
    show bgp ipv4 unicast <prefix>              why did it win or lose?
    show ip route <prefix>
    show bgp neighbor <ip> | include prefix|max|Notification

**Watch out for.** If you cannot see received-routes at all, you are
probably missing `soft-reconfiguration inbound` or route refresh
capability, and you are reasoning from incomplete data. Fix your
visibility before you theorise about policy.

In an ISP NOC, this scenario often ends at the peer rather than at you,
so know your route-server and looking-glass options in advance.

**References:** [RFC 4271,
BGP-4](https://www.rfc-editor.org/rfc/rfc4271.html) · [RFC 7454, BGP
Operations and Security](https://www.rfc-editor.org/rfc/rfc7454.html)

### Q14. A gateway failover didn't happen when the primary router failed

*Tier: L3. Safety: read-only.*

**Short answer.** First-hop redundancy failed to trigger or failed to
complete. Check whether the standby actually saw the primary disappear,
whether tracking was configured for the thing that actually broke, and
whether the switching layer relearned the virtual MAC.

**What is actually going on.** HSRP, VRRP and GLBP protect against the
*router* dying. They do not, by default, protect against the router's
uplink dying, which is a far more common failure. If the primary keeps
sending hellos while its WAN interface is down, the standby has no
reason to take over and traffic disappears into a healthy-looking
router.

Object tracking is what closes that gap. You track the uplink, or
better, an IP SLA probe that tests real reachability, and decrement the
priority when it fails. BFD gives you sub-second detection where the
hardware supports it, which matters because default HSRP hold times are
measured in seconds and voice notices.

The other half of the failure is Layer 2. After a failover, the new
active router must gratuitously ARP so hosts and switches relearn the
virtual MAC. If those frames are lost or filtered, hosts keep sending to
the old MAC for the duration of their ARP cache.

**How to check**

                                                         [read-only]
    show standby brief                       HSRP state, priority, preempt
    show vrrp brief
    show standby <if> | include Track|Priority|Preempt
    show track                               is anything actually tracked?
    show ip sla statistics
    show bfd neighbors detail
    show logging | include HSRP|VRRP|TRACK

    On the access switch                                 [read-only]
    show mac address-table address <virtual-mac>

**Watch out for.** Check `preempt`. Without it, a recovered primary
never takes back the active role, which is fine until the day the
standby fails and everyone discovers there was no redundancy left.

Also confirm the tracked object matches the real risk. Tracking the
local interface line protocol misses a failure two hops upstream, and
that is exactly the failure that takes your internet away.

**References:** [RFC 5798,
VRRPv3](https://www.rfc-editor.org/rfc/rfc5798.html) · [RFC 5880,
Bidirectional Forwarding
Detection](https://www.rfc-editor.org/rfc/rfc5880.html)

## Chapter 2. DNS and DHCP

*Scenarios Q15 to Q22. Tier mix: 4 L1, 4 L2.*

### Orientation

DNS and DHCP are the two services that make a network usable by humans
rather than by people who memorise IP addresses. They break in ways that
look like network faults but are not, which is why they generate so many
misrouted tickets.

**DHCP** hands out addresses. A client shouts into the broadcast domain,
a server answers, and the client leases an address for a set period.
Because the request is a broadcast, it does not cross a router on its
own. Something has to relay it.

**DNS** turns names into addresses. Your client asks a resolver, the
resolver either knows the answer, has it cached, or goes and finds it by
walking down from the root servers. Almost every DNS problem is really a
question of *which* server answered and *when it cached that answer*.

One habit will save you hours: whenever a user reports something broken,
test by IP address as well as by name. That single comparison tells you
whether you are looking at a name resolution problem or a network
problem.

### Scenarios in this chapter

  -------------------------------------------------------------------------------------------------------------------------------------------------
  ID                                                                                 Scenario                                             Tier
  ---------------------------------------------------------------------------------- ---------------------------------------------------- ---------
  [Q15](#q15.-users-can-reach-ips-directly-but-not-by-hostname)                      Name resolution failing, IP working                  L1

  [Q16](#q16.-internal-dns-resolves-fine-but-external-domains-fail-intermittently)   External resolution intermittent                     L2

  [Q17](#q17.-a-new-laptop-cant-get-an-ip-address-on-the-network)                    DHCP failure on one client                           L1

  [Q18](#q18.-a-branch-office-dhcp-scope-is-exhausted-despite-low-headcount)         Scope exhaustion                                     L2

  [Q19](#q19.-a-dns-server-is-up-but-one-specific-domain-always-times-out)           Single zone failing                                  L2

  [Q20](#q20.-devices-are-getting-apipa-169.254.x.x-addresses)                       Link-local self-assignment                           L1

  [Q21](#q21.-a-dual-homed-server-intermittently-registers-the-wrong-ip-in-dns)      Dynamic DNS registration race                        L2

  [Q22](#q22.-after-a-dns-record-change-some-users-still-resolve-the-old-ip)         TTL and caching                                      L1
  -------------------------------------------------------------------------------------------------------------------------------------------------

### Q15. Users can reach IPs directly but not by hostname

*Tier: L1. Safety: read-only.*

**Short answer.** Reaching the same service on the same port by IP makes
name resolution the leading hypothesis. Confirm the client's resolver
settings, confirm that resolver is reachable on both UDP and TCP 53,
then query the DNS server directly to separate a client problem from a
server problem.

Say "leading hypothesis," not "proves." A successful connection by IP
tells you that one flow, on one protocol and port, worked. It does not
clear NAT, proxy policy, or application-layer filtering for anything
else, and it definitely does not clear the path your DNS queries take,
which may be entirely different.

**What is actually going on.** Resolution has several independent
failure points:

- The client's configured resolver, usually handed out by DHCP, so a
  scope option error breaks a whole subnet at once
- The resolver's cache, holding a stale or negative answer
- The DNS search suffix list, so a short name never becomes the FQDN you
  expect
- The local hosts file, which quietly overrides everything
- The upstream forwarder chain

Querying the authoritative server directly bypasses every cache and
answers one question cleanly: does this record exist at all?

**How to check**

    # Client configuration                              [read-only]
    ipconfig /all                            # Windows
    resolvectl status                        # Linux, systemd-resolved
    cat /etc/resolv.conf                     # Linux, classic

    # Split the problem in half                         [active test]
    nslookup host.example.com                # via the configured resolver
    nslookup host.example.com 8.8.8.8        # bypassing it
    dig @<internal-dns> host.example.com +norecurse
    dig host.example.com +trace              # walk down from the root

    # Is port 53 reachable at all?                      [active test]
    nc -vz <dns-server> 53                   # TCP

**Watch out for.** If `dig @<server>` works but the client fails, the
problem is the client resolver, the search suffix, or a local cache. If
`dig @<server>` also fails, the problem is the zone or the server. That
single test splits the problem space in half, so make it your first move
rather than your fifth.

**References:** [RFC 1034](https://www.rfc-editor.org/rfc/rfc1034.html)
· [RFC 1035, Domain Names](https://www.rfc-editor.org/rfc/rfc1035.html)

### Q16. Internal DNS resolves fine but external domains fail intermittently

*Tier: L2. Safety: active test.*

**Short answer.** Internal zones are answered locally and never leave
the building, so the fault sits somewhere in the recursion path. Several
hypotheses fit, and you need evidence to choose between them rather than
assuming one.

**What is actually going on.** Treat these as competing hypotheses, not
a diagnosis:

  ------------------------------------------------------------------------
  Hypothesis          What it looks like            How to test
  ------------------- ----------------------------- ----------------------
  Forwarder failure   Slow answers, then success;   Query each forwarder
  or failover         alternating results           individually

  DNSSEC validation   SERVFAIL for signed zones     Compare with and
  failure             only, consistent per domain   without `+cd`

  Packet loss on the  Random, affects all external  MTR to the forwarder
  path                names equally                 

  Rate limiting or    Fails under load, recovers    Check resolver and
  query quota         when quiet                    firewall logs

  Large response or   Small answers fine, large     Compare a small query
  EDNS problem        answers fail                  with a large one

  TCP 53 blocked      Fails only where fallback to  Query with `+``tcp`
                      TCP is needed                 
  ------------------------------------------------------------------------

The last two are worth understanding together. DNS classically limits
UDP responses to 512 bytes and falls back to TCP for anything larger.
EDNS0 negotiates bigger UDP payloads, which some middleboxes then
fragment or drop. Plenty of firewall policies permit UDP 53 and quietly
omit TCP 53, and that produces exactly this "internal fine, external
flaky" pattern.

**How to check**

                                                        # [active test]
    dig @<forwarder> example.com +short
    dig @<forwarder> example.com +tcp              # does TCP 53 work?
    dig @<forwarder> example.com +bufsize=4096     # large EDNS0 response
    dig @<forwarder> <signed-domain> +dnssec       # validation behaviour
    dig @<forwarder> <signed-domain> +cd           # checking disabled
    nc -vz <forwarder> 53                          # TCP reachability
    mtr -rwc 100 <forwarder>                       # loss on the path
    Windows Server DNS                                   [read-only]
      Get-DnsServerForwarder
      Event Viewer > DNS Server log

**Watch out for.** Comparing a query answered with `+``dnssec` against
the same query with `+cd` tells you whether validation is the cause,
because `+cd` asks the resolver to skip validation. Do not use a domain
that is deliberately broken as a general size test. Test size with
`+``bufsize`, and test validation with a real signed zone.

**References:** [RFC 6891,
EDNS(0)](https://www.rfc-editor.org/rfc/rfc6891.html) · [RFC 7766, DNS
over TCP](https://www.rfc-editor.org/rfc/rfc7766.html) · [RFC 4035,
DNSSEC Protocol](https://www.rfc-editor.org/rfc/rfc4035.html)

### Q17. A new laptop can't get an IP address on the network

*Tier: L1. Safety: read-only.*

**Short answer.** Walk the DHCP path in order. Is the port up and in the
right VLAN, is port security or 802.1X blocking it, does the gateway
have an `ip`` helper-address`, and does the scope have free leases? If
all four pass, capture at the switch.

**What is actually going on.** DHCP discovery is a broadcast, so it does
not cross a router without a relay agent forwarding it as unicast to the
server. On a brand new VLAN, the missing helper address is the classic
cause.

On an existing VLAN where everyone else is fine, the cause is local to
that port or that client. Port security may have err-disabled it after a
MAC violation. 802.1X authentication may have failed and left the port
unauthorised. The port may simply be in the wrong VLAN.

An exhausted scope affects every new client, not just one laptop, which
is a useful way to tell the two apart quickly.

**How to check**

    Switch                                               [read-only]
      show interface <if> status                connected? err-disabled?
      show port-security interface <if>
      show authentication sessions interface <if> details
      show interface <if> switchport            correct VLAN?

    Router or SVI                                        [read-only]
      show run interface vlan <id> | include helper

    DHCP server                                          [read-only]
      Get-DhcpServerv4ScopeStatistics -ComputerName <srv>     Windows
      journalctl -u kea-dhcp4                                 Kea
      dhcp-lease-list                                         ISC

    Client                                               [active test]
      ipconfig /release ; ipconfig /renew
      dhclient -v <interface>

**Watch out for.** DHCP snooping enabled on the access switch without a
trusted uplink port blocks every legitimate OFFER. It is a common
self-inflicted cause after a security hardening project, and it looks
exactly like a dead DHCP server.

**References:** [RFC 2131,
DHCP](https://www.rfc-editor.org/rfc/rfc2131.html) · [RFC 3046, DHCP
Relay Agent Information
Option](https://www.rfc-editor.org/rfc/rfc3046.html)

### Q18. A branch office DHCP scope is exhausted despite low headcount

*Tier: L2. Safety: read-only.*

**Short answer.** Addresses are being consumed faster than they are
released. Look at the lease table before you look at anything else,
because the pattern in it names the cause.

**What is actually going on.** A lease is held for its full duration
whether or not the device is still there. In a site with guest phones,
contractor laptops and roaming mobiles, an eight-day lease against a /24
can exhaust with only thirty staff.

The obvious explanation, a chatty client draining the pool, does not
hold up. A device that repeatedly sends DISCOVER using the *same* client
identifier normally gets offered the *same* address each time. Repeat
requests alone do not consume the pool.

Scope exhaustion needs addresses to keep being allocated to apparently
new clients, which means one of:

- **Randomised MAC addresses.** Modern phones and laptops present a
  randomised MAC address to each network by default. On most platforms
  that address stays stable for a given SSID, but rotating modes,
  forgetting and rejoining the network, and periodic re-randomisation on
  some operating systems all make one device look like several. In guest
  and BYOD networks this is now a leading cause.
- **A changing client identifier.** Some clients send a DHCP client-ID
  that varies across reboots or firmware states, so the server treats
  each request as a new device.
- **Deliberate spoofing.** A starvation attack cycling through
  fabricated MAC addresses.
- **Stale leases plus genuine churn.** Not exhaustion by itself, but it
  shrinks the usable pool until normal churn overflows it.

**How to check**

    Windows                                              [read-only]
      Get-DhcpServerv4Scope
      Get-DhcpServerv4ScopeStatistics
      Get-DhcpServerv4Lease -ScopeId <x> | Group-Object ClientId

    ISC DHCP / Kea                                       [read-only]
      dhcp-lease-list --all
      grep -c "DHCPACK" /var/log/syslog

    Read the lease table for
      - many leases, each with a distinct and unfamiliar MAC prefix
      - lease start times clustered into one short window
      - the same hostname appearing against several addresses

**Watch out for.** Before you extend the subnet, work out which of the
causes above you have. Randomised MAC addresses call for scope sizing
plus shorter leases. A starvation attack calls for DHCP snooping with
rate limiting and port security. Those are very different responses to
an identical-looking symptom.

**Reference:** [RFC 2131,
DHCP](https://www.rfc-editor.org/rfc/rfc2131.html)

### Q19. A DNS server is up, but one specific domain always times out

*Tier: L2. Safety: active test.*

**Short answer.** The problem is scoped to that zone, not to the server.
Either the domain's authoritative servers are unreachable from your
resolver, a conditional forwarder for that zone points somewhere broken,
or a delegation is stale. Walk the delegation and query the authority
directly.

**What is actually going on.** A resolver answering every other query is
healthy. A timeout on one zone means recursion for that zone is failing,
and `dig +trace` shows exactly where by walking from the root through
each delegation.

Common causes: a conditional forwarder still pointing at a domain
controller that was decommissioned after a merger, a partner's firewall
newly blocking your resolver's source address, a lame delegation where
the parent names a server that is not authoritative, or a zone whose
last remaining nameserver is offline.

**How to check**

                                                        # [active test]
    dig example.com +trace              # where does the chain break?
    dig NS example.com
    dig @<authoritative-ns> example.com # query the authority directly
    dig @<your-resolver> example.com +norecurse
    nc -vz <authoritative-ns> 53
    Windows Server                                       [read-only]
      Get-DnsServerZone
      Get-DnsServerZone -Name example.com | Select MasterServers

**Watch out for.** `dig +trace` is one of the most useful DNS commands
you can learn, and surprisingly few L1 candidates know it. Saying "I
would run `dig +trace` and see which delegation stops responding"
signals operational experience, because it describes what experienced
engineers actually do.

**References:** [RFC 1034](https://www.rfc-editor.org/rfc/rfc1034.html)
· [RFC 8499, DNS
Terminology](https://www.rfc-editor.org/rfc/rfc8499.html)

### Q20. Devices are getting APIPA (169.254.x.x) addresses

*Tier: L1. Safety: read-only.*

**Short answer.** The client did not obtain a usable DHCP configuration,
so it self-assigned a link-local address. Establish the blast radius
first, then work the DHCP path: service, relay, and the network between
them.

**What is actually going on.** A host that fails DHCP self-assigns from
169.254.0.0/16 under the link-local specification. That address works
only on the local link and carries no gateway, which is why affected
users can sometimes see each other and nothing else.

Do not over-read it. APIPA proves that no usable DHCP configuration was
obtained. It does not prove the client's stack is healthy. A host
firewall blocking UDP 68, a broken or disabled DHCP client service, a
NIC driver problem, a failed 802.1X supplicant, or the port sitting in
the wrong VLAN all produce the same result.

**How to check**

    Start with blast radius, because it points you at the layer
      One host        -> port, VLAN, port security, 802.1X, host firewall, driver
      One VLAN        -> ip helper-address, relay config, that subnet's scope
      Everyone        -> DHCP service down, or scope database problem

    Commands                                             [read-only]
      show run interface vlan <id> | include helper
      show ip dhcp binding                if the switch is the DHCP server
      Get-Service DHCPServer                            Windows
      systemctl status isc-dhcp-server                  Linux

                                                         [active test]
      tcpdump -i <if> -n port 67 or port 68
        Do DISCOVERs leave the client?
        Do they arrive at the server?
        Does an OFFER come back and get dropped on the way?

**Watch out for.** Establishing the blast radius before touching
anything cuts the search space immediately, and it is the structured
habit an L1 role depends on. A capture at the client and at the server,
compared, tells you which direction is failing.

**Reference:** [RFC 3927, IPv4 Link-Local
Addresses](https://www.rfc-editor.org/rfc/rfc3927.html)

### Q21. A dual-homed server intermittently registers the wrong IP in DNS

*Tier: L2. Safety: read-only.*

**Short answer.** Both NICs are performing dynamic DNS registration and
overwriting each other, so the A record alternates. Disable registration
on the non-primary interface, or set interface metrics so one path is
deterministically preferred.

**What is actually going on.** Under dynamic update, a host registers
whatever address it believes is primary. With two NICs, each can
register its own address and overwrite the other, producing a record
that changes on every registration cycle. Clients cache whichever value
they happened to receive, so roughly half of them break at any moment.

That is why the symptom is intermittent. The record is correct about
half the time, which makes it maddening to reproduce on demand.

**How to check**

    # Windows                                            [read-only]
    Get-DnsClient | Select InterfaceAlias, RegisterThisConnectionsAddress
    Get-NetIPInterface | Select InterfaceAlias, InterfaceMetric

    # Fix                                                [change approval]
    Set-DnsClient -InterfaceAlias "NIC2" -RegisterThisConnectionsAddress $false
    On the DNS server                                    [read-only]
      Get-DnsServerResourceRecord -ZoneName <zone> -Name <host>
      Check the timestamp. A record rewritten every few minutes confirms the race.

**Watch out for.** The same root cause produces intermittent Kerberos
and service principal failures on multi-homed domain controllers and SQL
servers, which is a much more expensive symptom than a wrong A record.
Mention that downstream impact, because it is the part of the blast
radius that costs most.

**Reference:** [RFC 2136, Dynamic Updates in the
DNS](https://www.rfc-editor.org/rfc/rfc2136.html)

### Q22. After a DNS record change, some users still resolve the old IP

*Tier: L1. Safety: read-only.*

**Short answer.** Caching. The old answer is still held by client
resolvers, intermediate forwarders and downstream ISP resolvers until
the TTL expires. Flush what you control and wait out the TTL for
everything else.

**What is actually going on.** Every cached answer carries the TTL that
was in force *when it was cached*, not the TTL you set afterwards.
Lowering the TTL after publishing a change does nothing for resolvers
that already hold the old record.

That is why planned migrations lower the TTL to 300 seconds or less at
least one full old-TTL period *before* cutover, then raise it again once
things settle. Browsers and application runtimes add their own caching
on top of the OS resolver, and some ignore TTL entirely.

**How to check**

                                                        # [read-only]
    dig host.example.com                     # watch the TTL count down
    dig @<authoritative-ns> host.example.com # what the truth actually is
    dig @8.8.8.8 host.example.com            # what a public resolver still holds

    # Flush                                              [read-only / low risk]
    ipconfig /flushdns                       # Windows client
    resolvectl flush-caches                  # Linux, systemd
    sudo dscacheutil -flushcache             # macOS
    Clear-DnsServerCache                     # Windows DNS server
    rndc flush                               # BIND

**Watch out for.** The mature answer includes the planning, not just the
flush command. "We drop TTL to 300 seconds a day before the migration
window, cut over, verify, then restore it" is a change management answer
rather than a troubleshooting one.

**References:** [RFC 1035](https://www.rfc-editor.org/rfc/rfc1035.html)
· [RFC 8767, Serving Stale
Data](https://www.rfc-editor.org/rfc/rfc8767.html)

# Part II. Security, Remote Access and Wireless

Security controls, tunnels and radio links all fail in ways that look
like something else. A firewall drop looks like an outage, a tunnel that
is up can still pass nothing, and a strong Wi-Fi signal can still mean
poor performance. Part II teaches you to find the stage where traffic
actually stops.

## Chapter 3. Firewall and Security

*Scenarios Q23 to Q34. Tier mix: 9 L2, 3 L3.*

### Orientation

A firewall decides whether a packet is allowed through. That sounds
simple until you realise a modern firewall makes that decision in
several stages, and a packet can die at any of them.

Roughly, a packet passes through: routing lookup, NAT, session lookup,
access policy, and then inspection engines like IPS, URL filtering and
TLS decryption. Your job when something is blocked is to find out *which
stage* dropped it, because "the firewall is blocking it" is not a
diagnosis anyone can act on.

Two concepts worth understanding before you go further:

**Stateful means the firewall remembers.** Once a session is allowed,
return traffic is permitted automatically because the firewall tracks
the connection. This is why asymmetric routing is so painful behind
firewalls: the return packet arrives at a device that has no record of
the session and drops it.

**Order matters.** Access lists are evaluated top to bottom and stop at
the first match. A permit rule at line 400 is irrelevant if a deny at
line 12 matched first.

Most vendors give you a tool that answers the "which stage" question in
one command. Learn yours. It will save you more time than anything else
in this chapter.

### Scenarios in this chapter

  ------------------------------------------------------------------------------------------------------------------------------------------------------------------
  ID                                                                                                  Scenario                                            Tier
  --------------------------------------------------------------------------------------------------- --------------------------------------------------- ----------
  [Q23](#q23.-traffic-is-allowed-by-an-acl-but-still-blocked)                                         Policy evaluation order                             L2

  [Q24](#q24.-after-a-firewall-rule-update-voip-calls-drop-after-about-30-seconds)                    Calls dropping at a fixed interval                  L2

  [Q25](#q25.-users-cant-access-a-site-that-used-to-work-now-blocked-by-url-filtering)                Web filtering and decryption                        L2

  [Q26](#q26.-a-perimeter-firewall-shows-a-spike-in-denied-connections-from-one-external-ip)          Scan or attack triage                               L2

  [Q27](#q27.-a-site-to-site-tunnel-is-up-but-no-traffic-passes)                                      IPsec phase and proxy IDs                           L2

  [Q28](#q28.-an-internal-server-suddenly-cant-be-reached-from-outside-after-a-change)                NAT and publishing                                  L2

  [Q29](#q29.-a-users-laptop-is-quarantined-by-nac-without-explanation)                               802.1X and posture                                  L2

  [Q30](#q30.-repeated-login-failures-from-many-source-ips-against-one-admin-account)                 Credential attack response                          L2

  [Q31](#q31.-after-enabling-deep-packet-inspection-throughput-drops)                                 Inspection capacity                                 L3

  [Q32](#q32.-a-misconfigured-acl-blocked-a-critical-application-at-2-am)                             Change control failure                              L2

  [Q33](#q33.-users-can-browse-sites-but-file-downloads-consistently-fail-or-hang)                    Large transfers failing                             L3

  [Q34](#q34.-remote-sites-behind-different-firewall-vendors-report-inconsistent-vpn-compatibility)   Interoperability                                    L3
  ------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Q23. Traffic is allowed by an ACL but still blocked

*Tier: L2. Safety: read-only.*

**Short answer.** Look for an earlier matching deny, since evaluation
stops at the first match. Then check NAT and routing, and look for a
second enforcement layer: zone policy, an object-group change, stateful
session state, or the implicit deny at the end of a list applied in the
other direction.

**What is actually going on.** "Allowed by an ACL" is a statement about
one rule, not about the outcome. Packets can die in several other
places:

- A higher rule in the same list matched first
- An ACL on the other interface, or the other direction, dropped it
- NAT rewrote the address so it no longer matches your permit
- Zone-based policy evaluated after the interface ACL denied it
- On a stateful device, a return packet with no matching session entry
  was dropped, which is what makes asymmetric routing so miserable
  behind a firewall pair

**How to check**

    Cisco ASA                                            [read-only]
      packet-tracer input inside tcp 10.1.1.10 1234 10.2.2.20 443 detailed
      show access-list <name> | include hitcnt
      show conn address <ip>
      show nat detail
      show asp drop                    accelerated path drop reasons

    Palo Alto                                            [read-only]
      test security-policy-match from trust to untrust source <ip> \
           destination <ip> protocol 6 destination-port 443
      show session all filter source <ip>

    Fortinet                                             [service-affecting]
      diagnose debug flow filter addr <ip>
      diagnose debug flow trace start 20

**Watch out for.** `packet-tracer` on ASA and
`test security-policy-match` on Palo Alto answer this question
definitively by naming the exact phase and rule that dropped the packet.
Knowing your platform's version of that tool by name is a strong signal
in an interview.

**Reference:** [RFC 2979, Behavior of and Requirements for Internet
Firewalls](https://www.rfc-editor.org/rfc/rfc2979.html)

### Q24. After a firewall rule update, VoIP calls drop after about 30 seconds

*Tier: L2. Safety: read-only.*

**Short answer.** Start with the SIP dialogue, not with timers. Capture
the signalling and find out which side sends BYE, or whether a
transaction failed. Calls that fail at roughly 30 seconds most often
point at a SIP transaction problem, commonly a missing ACK after the 200
OK, which is exactly the kind of thing a SIP ALG change causes.

**What is actually going on.** It is tempting to blame a UDP idle
timeout, but think about whether that mechanism fits. Once a call is
established, RTP flows continuously in both directions, and that traffic
refreshes the session state. An idle timeout should not fire under a
healthy bidirectional media stream.

What does fit a \~30 second failure:

- **A missing ACK to the 200 OK.** The caller answers, the server
  retransmits its 200 OK, gets no ACK, and eventually gives up and tears
  the call down. If your firewall's SIP ALG rewrites addresses in the
  signalling incorrectly, the ACK goes somewhere unreachable.
- **A broken or newly enabled SIP ALG.** Enabling it and disabling it
  both break calls, in different ways, which is why blanket advice about
  ALGs is useless.
- **One-way or absent media plus a media-inactivity timer.** If RTP only
  flows one way, the reverse pinhole can idle out and a media inactivity
  supervision timer can end the call. Here the UDP timeout genuinely
  does matter, but as a second-order effect of the media problem, not as
  the root cause.
- **Session or registration timers set unusually low.** Less likely at
  30 seconds, but check.

**How to check**

    Capture and read the SIP dialogue first             [read-only]
      Who sends BYE, and with what Reason header?
      Is there a 200 OK with no matching ACK?
      Are the SDP addresses in the messages reachable from the other side?

    Cisco                                                [service-affecting]
      debug ccsip messages
      show sip-ua connections
      show voip rtp connections

    Cisco ASA                                            [read-only]
      show service-policy inspect sip
      show conn protocol udp
      show run timeout

    Media check                                          [active test]
      tcpdump -i <if> -n udp portrange 16384-32768
      Is RTP flowing in both directions, or only one?

**Watch out for.** Timing that lands on a precise, repeating value is a
timer somewhere. Random drops are congestion or loss. The distinction is
worth stating, but do not let it push you into guessing *which* timer
before you have read the signalling.

**References:** [RFC 3261,
SIP](https://www.rfc-editor.org/rfc/rfc3261.html) · [RFC 4787, NAT UDP
Requirements](https://www.rfc-editor.org/rfc/rfc4787.html)

### Q25. Users can't access a site that used to work, now blocked by URL filtering

*Tier: L2. Safety: read-only.*

**Short answer.** Read the logs to find which rule and which category
produced the block. Check whether a category database update
reclassified the site. Then rule out a TLS decryption failure, which
looks like a block but is not one.

**What is actually going on.** Three different failures look identical
to the user:

A **genuine policy block** logs a category and a rule ID.
Straightforward.

A **reclassification** means the vendor's database moved the domain,
often after it changed ownership or started hosting user content. The
fix is a recategorisation request to the vendor, not a local rule.

A **decryption failure** is the sneaky one. If the site pins its
certificate, requires a client certificate, or negotiates something the
inspection engine cannot handle, the connection fails in a way that
resembles a block but appears in the decryption log as an error rather
than in the policy log as a hit.

**How to check**

    In this order                                        [read-only]
      1. Filter or threat log for that source IP at that time
           -> rule name, category, action
      2. Vendor category lookup for the URL
      3. Decryption log for the same session
           -> pinned certificate, unsupported cipher, expired CA
      4. Test with decryption bypassed for that destination

    Palo Alto
      show log url query equal "( addr.src eq <ip> )"
      show log decryption
    Fortinet                                             [service-affecting]
      diagnose debug application urlfilter -1

**Watch out for.** Certificate-pinned applications, including many
banking and update clients, must go on a decryption exclusion list. They
will never work through TLS inspection no matter what the URL policy
says. Recognising that pattern saves hours.

**Reference:** [RFC 8446, TLS
1.3](https://www.rfc-editor.org/rfc/rfc8446.html)

### Q26. A perimeter firewall shows a spike in denied connections from one external IP

*Tier: L2. Safety: read-only.*

**Short answer.** Characterise before you react. Work out the pattern,
check whether anything was *permitted* rather than denied, apply a
temporary block or rate limit with an expiry, and escalate through the
security incident process with the evidence attached.

**What is actually going on.** Internet-facing firewalls log denied
traffic continuously. Background scanning is constant and mostly noise.
What lifts it from noise to incident is any of:

- A permit alongside the denies, meaning something got through
- A scan walking your address space in order, meaning targeted
  reconnaissance
- A source that changes technique after being blocked, meaning a human
  is present
- A match against threat intelligence

The mistake to avoid is a permanent block from a single spike. Attacker
infrastructure is disposable. Legitimate shared addresses, like a
partner's NAT gateway or a cloud egress IP, are not.

**How to check**

                                                         [read-only]
      1. Denied vs permitted from that source in the same window
      2. Destination spread    many hosts = horizontal scan
      3. Port spread           many ports on one host = vertical scan
      4. Rate and timing       steady = automated, bursty = interactive
      5. Threat intel and WHOIS on the source
      6. Correlate with IPS and authentication logs for the same window

    Then                                                 [change approval]
      - temporary block or rate limit, with an expiry date
      - security incident opened with the log excerpt attached
      - no permanent blacklist without confirming who owns the address

**Watch out for.** The senior version of this answer leads with "check
what was permitted." Denied traffic is the firewall doing its job.
Permitted traffic from a scanning source is the actual incident, and it
is what junior analysts forget to look for.

**Reference:** [NIST SP 800-61 Rev. 3, Incident
Response](https://csrc.nist.gov/pubs/sp/800/61/r3/final)

### Q27. A site-to-site tunnel is up but no traffic passes

*Tier: L2. Safety: read-only.*

**Short answer.** Confirm both Phase 1 and Phase 2 are established,
verify the proxy IDs match exactly on both peers, confirm routing
actually sends traffic into the tunnel, and check for NAT rewriting
addresses before they reach the encryption domain.

**What is actually going on.** "Tunnel is up" usually means Phase 1
completed, which proves the peers authenticated and nothing more.

Traffic needs a Phase 2 SA whose proxy IDs match on both sides. A /24 on
one end against a /16 on the other fails to negotiate even though both
configs look perfectly reasonable read on their own.

Beyond that, the tunnel is only used if routing directs traffic to it or
the crypto ACL classifies it as interesting. A NAT rule that translates
the source before encryption makes the packet miss the encryption domain
entirely.

**How to check**

    Cisco IOS / ASA                                      [read-only]
      show crypto ikev2 sa                          Phase 1
      show crypto ipsec sa                          Phase 2
        -> compare pkts encaps against pkts decaps
      show crypto session detail

    Palo Alto                                            [read-only]
      show vpn ike-sa ; show vpn ipsec-sa ; show vpn flow

    Checklist
      [ ] Phase 1 up            [ ] Phase 2 up
      [ ] Proxy IDs identical on both peers
      [ ] Route points into the tunnel
      [ ] No NAT applied before encryption, or a NAT-exempt rule exists
      [ ] Both peers agree on PFS group and lifetime

**Watch out for.** `pkts`` ``encaps` rising while `pkts`` ``decaps`
stays at zero means your side is encrypting and the far side is not
returning anything. That one counter comparison tells you which end owns
the problem.

**References:** [RFC 7296,
IKEv2](https://www.rfc-editor.org/rfc/rfc7296.html) · [RFC 4301,
Security Architecture for
IP](https://www.rfc-editor.org/rfc/rfc4301.html)

### Q28. An internal server suddenly can't be reached from outside after a change

*Tier: L2. Safety: read-only.*

**Short answer.** Three independent things must be true: the translation
exists and points at the right internal address, policy permits the
translated flow, and the server is actually listening. Test from outside
and from inside separately.

**What is actually going on.** Publishing a server depends on objects
that a change can break separately.

Object-group edits are a frequent culprit, because changing a group used
by several rules silently changes all of them. A server that stopped
listening, whether from a crashed service, a changed bind address, or a
host firewall coming back on after a patch, produces an identical
external symptom. A change to the outside interface address, or a new
upstream device doing its own NAT, breaks publishing without anyone
touching your config at all.

**How to check**

    # From outside                                       [active test]
    nc -vz <public-ip> 443
    curl -vk https://<public-ip>/
    On the firewall                                      [read-only]
      show nat detail    /  show xlate
      packet-tracer input outside tcp <src> 1234 <public-ip> 443 detailed
      show access-list | include hitcnt

    On the server                                        [read-only]
      netstat -tulpn | grep 443              Linux
      Get-NetTCPConnection -State Listen     Windows
      systemctl status <service>

**Watch out for.** Run `packet-tracer` from the *outside* interface with
the real public source address. Simulating from the wrong interface
gives you a confident and entirely misleading result, and people act on
it.

**References:** [RFC 3022, Traditional IP
NAT](https://www.rfc-editor.org/rfc/rfc3022.html) · [RFC 5382, NAT
Requirements for TCP](https://www.rfc-editor.org/rfc/rfc5382.html)

### Q29. A user's laptop is quarantined by NAC without explanation

*Tier: L2. Safety: read-only.*

**Short answer.** Read the failure reason in the NAC console instead of
guessing. It will tell you whether authentication failed or posture
assessment failed, and those have completely different fixes.

**What is actually going on.** NAC combines two independent gates.
Authentication answers "who are you" through 802.1X and EAP. Posture
answers "are you compliant." Fail either and you land in quarantine, and
the user-visible symptom is the same.

The console separates them. An authentication failure shows an EAP or
certificate error and a rejected RADIUS exchange. A posture failure
shows a successful authentication followed by a compliance verdict.

In practice, the two most common real causes are expired machine
certificates after a CA renewal, and antivirus definitions that aged out
while a laptop was on leave.

**How to check**

    Cisco ISE                                            [read-only]
      Operations > RADIUS > Live Logs   filter by MAC or username
        -> the Failure Reason field names the exact cause
      Operations > Reports > Posture Assessment by Endpoint

    Switch                                               [read-only]
      show authentication sessions interface <if> details
      show dot1x interface <if> details

    Client                                               [read-only]
      Windows: Event Viewer > Applications and Services Logs >
               Microsoft > Windows > Wired-AutoConfig
      certlm.msc      is the machine certificate present and valid?

**Watch out for.** The Failure Reason field answers this question
directly. Guessing at posture rules instead of reading the log suggests
you have not used the platform.

**References:** [IEEE
802.1X](https://standards.ieee.org/ieee/802.1X/7345/) · [RFC 3748,
EAP](https://www.rfc-editor.org/rfc/rfc3748.html)

### Q30. Repeated login failures from many source IPs against one admin account

*Tier: L2. Safety: read-only.*

**Short answer.** Treat it as credential stuffing or a distributed brute
force. Establish first whether anything succeeded, because containment
and investigation diverge completely at that point. Then lock or reset,
verify lockout and MFA, block or rate-limit the sources, and escalate.

**What is actually going on.** Many sources against one account is a
deliberate evasion of both per-source rate limiting and per-account
lockout. Each source stays under the threshold while the aggregate rate
stays high.

That pattern also implies the attacker has a validated username, which
usually means it leaked or is guessable. Password spraying is the mirror
image, one password against many accounts, and it evades lockout
differently. Naming which pattern you are seeing matters.

**How to check**

                                                         [read-only]
      1. Any successful authentication from those sources?
      2. Was MFA satisfied on any success, or bypassed?
      3. Is the account privileged, and what does it reach?
      4. Source geography and ASN spread
      5. Are other accounts targeted, or only this one?

    Windows                                              [read-only]
      Event ID 4625 failed, 4624 success, 4740 lockout
      Get-WinEvent -FilterHashtable @{LogName='Security';Id=4625}

    Immediate actions                                    [change approval]
      - reset credentials AND revoke active sessions and tokens
      - confirm lockout threshold and MFA enforcement
      - rate-limit or geo-restrict the admin surface
      - open a security incident; preserve logs before rotation

**Watch out for.** Revoking sessions and tokens matters as much as
resetting the password. An attacker holding a valid session cookie or
refresh token is completely unaffected by a password change, and
forgetting that step is a common real-world gap.

**References:** [NIST SP 800-63 Revision 4, Digital
Identity](https://pages.nist.gov/800-63-4/) · [MITRE ATT&CK T1110, Brute
Force](https://attack.mitre.org/techniques/T1110/)

### Q31. After enabling deep packet inspection, throughput drops

*Tier: L3. Safety: read-only.*

**Short answer.** Inspection, and TLS decryption in particular, is
expensive and often bypasses hardware acceleration. Measure CPU and
session load, compare against the platform's *inspected* throughput
rating rather than its headline figure, and apply inspection
selectively.

**What is actually going on.** Vendor datasheets quote several
throughput numbers and they differ by large multiples: raw firewall
throughput, throughput with threat prevention, and throughput with TLS
decryption.

Decryption requires terminating and re-establishing every session,
multiplying session count, memory and CPU per connection. Many platforms
accelerate plain forwarding in hardware and drop to software for
inspected flows, so enabling inspection does not degrade performance
gradually. It moves traffic onto a different and much slower path.

The engineering answer is selective policy, decryption exclusion lists,
and capacity planning against the inspected figure.

**How to check**

    Palo Alto                                            [read-only]
      show system resources follow
      show session info                 session count vs platform maximum
      show running resource-monitor hour

    Fortinet                                             [read-only]
      get system performance status
      diagnose sys session stat
      diagnose npu npu-feature          is hardware offload still engaged?

    Method                                               [active test]
      1. Baseline with iperf3 before the change
      2. Enable inspection on a limited policy only
      3. Re-measure and compare against the inspected datasheet figure

**Watch out for.** Ask which datasheet number the platform was sized
against. A firewall bought on a 20 Gbps raw figure and then asked to
decrypt at 3 Gbps was under-specified at purchase, and no amount of
tuning fixes that. Naming it as a sizing problem rather than a
configuration problem is the L3 answer.

**Reference:** [RFC 8404, Effects of Pervasive Encryption on
Operators](https://www.rfc-editor.org/rfc/rfc8404.html)

### Q32. A misconfigured ACL blocked a critical application at 2 AM

*Tier: L2. Safety: change approval.*

**Short answer.** The failure is process, not syntax. No peer review, no
simulated test, no pre-approved rollback, no post-change verification.
Fix it with mandatory review, policy simulation before commit, staged
deployment, and an automatic revert timer.

**What is actually going on.** Firewall and ACL changes are unusually
dangerous because their blast radius is invisible in the diff. Adding a
deny above an existing permit changes behaviour for every flow that
permit used to match, and nothing in the diff shows you which flows
those were.

Mature controls attack that directly: hit-count review before deleting
or modifying a rule, simulated policy tests run *before* commit, staged
rollout to one site, and a monitored verification window before the
change is declared complete.

**How to harden**

    Pre-change                                           [change approval]
      - peer review, with the reviewer named in the change ticket
      - hit-count review on any rule being modified or removed
      - simulate known-good flows: packet-tracer, test security-policy-match
      - written rollback commands, tested, in the ticket

    During
      - Junos:      commit confirmed 10
      - Palo Alto:  config snapshot plus scheduled revert
      - IOS XE:     configure terminal revert timer 10

    Post-change
      - run the documented verification tests
      - watch monitoring for one full interval before closing

**Watch out for.** The strongest version of this answer names the
specific control that would have caught it, usually a hit-count review
showing the rule was still in use, or a simulated test for the
application's flow. Generic "we should have change control" is an L1
answer.

**References:** [NIST SP 800-41 Rev. 1, Firewall
Policy](https://csrc.nist.gov/pubs/sp/800/41/r1/final) · [ITIL 4 Change
Enablement](https://www.axelos.com/certifications/itil-service-management)

### Q33. Users can browse sites but file downloads consistently fail or hang

*Tier: L3. Safety: active test.*

**Short answer.** A path MTU discovery black hole is a strong
hypothesis, especially if there is a tunnel in the path, but it is not
the only thing that fits. Run the DF-bit test to gather evidence, and
check the alternatives before you commit to it.

**What is actually going on.** The PMTUD story goes like this. TCP
negotiates a maximum segment size at handshake, but handshake packets
are small and succeed regardless of the real path MTU. When bulk
transfer starts, full-size segments hit a link with a smaller MTU. With
DF set, the intermediate router drops the packet and returns ICMP Type 3
Code 4 telling the sender the correct MTU. Firewalls that block all ICMP
kill that message, so the sender never learns and retransmits the same
oversized segment forever.

That fits the symptom well. So do several other things, and a good
engineer rules them out rather than assuming:

  -----------------------------------------------------------------------
  Alternative                   Tell
  ----------------------------- -----------------------------------------
  Proxy, DLP or antivirus file  Fails at a consistent file size, logged
  size limit                    on the proxy

  Content filtering on file     Fails by extension, not by size
  type                          

  Server-side timeout           Fails after a consistent duration, not a
                                consistent size

  Storage or backend fault      Server logs show the error, network is
                                clean

  Application-level limit       Fails only for one application
  -----------------------------------------------------------------------

Use the DF-bit sweep as evidence for or against PMTUD, not as a
formality on the way to a conclusion you already reached.

**How to check**

    # Find the real path MTU by bisection                # [active test]
    ping -M do -s 1472 <dest>        # Linux: 1472 + 28 = 1500
    ping -f -l 1472 <dest>           # Windows
    tracepath <dest>                 # reports MTU changes per hop
    Cisco                                                [active test]
      ping <dest> size 1500 df-bit

    Fix, once PMTUD is confirmed                         [change approval]
      interface tunnel0
        ip tcp adjust-mss 1360
      Linux:
        iptables -t mangle -A FORWARD -p tcp --tcp-flags SYN,RST SYN \
          -j TCPMSS --clamp-mss-to-pmtu
      Firewall:
        permit icmp type 3 code 4 (fragmentation needed)

**Watch out for.** MSS clamping fixes TCP only. UDP applications over
the same path still need the MTU lowered or PMTUD working properly.

This is the classic symptom over GRE, IPsec, PPPoE and most overlays,
because encapsulation reduces the effective MTU. If everyone affected is
behind a tunnel, PMTUD moves to the front of your list.

**References:** [RFC 1191, Path MTU
Discovery](https://www.rfc-editor.org/rfc/rfc1191.html) · [RFC 2923, TCP
Problems with PMTUD](https://www.rfc-editor.org/rfc/rfc2923.html) · [RFC
4821, Packetization Layer
PMTUD](https://www.rfc-editor.org/rfc/rfc4821.html)

### Q34. Remote sites behind different firewall vendors report inconsistent VPN compatibility

*Tier: L3. Safety: read-only.*

**Short answer.** Implementation differences in NAT traversal, IKE
fragmentation and dead peer detection, made worse by firmware drift.
Build a compatibility matrix across sites rather than troubleshooting
them one at a time.

**What is actually going on.** IKEv2 and IPsec are standardised, but the
surrounding behaviour is not uniformly implemented. NAT-T detection, IKE
fragmentation support, DPD intervals, rekey behaviour and default
proposal sets all vary by vendor and by release.

A site whose local equipment performs NAT changes the negotiation
entirely, forcing UDP 4500 encapsulation that a stricter firewall may
not permit. Where IKE fragmentation is unsupported, large
certificate-based IKE_AUTH payloads fragment at the IP layer and get
dropped by middleboxes, which produces a failure that affects only
certificate authentication and only at some sites.

**How to check**

    Per site, record and compare                         [read-only]
      - vendor and exact firmware version
      - is the site behind NAT? was NAT-T detected in IKE_SA_INIT?
      - are UDP 500 and UDP 4500 permitted both ways?
      - is IKE fragmentation supported and enabled?
      - negotiated proposal: DH group, encryption, integrity, PRF, lifetime
      - authentication: PSK or certificate

    Commands
      show crypto ikev2 sa detail                        [read-only]
      tcpdump -i <if> -n 'udp port 500 or udp port 4500' [active test]
      debug crypto ikev2 platform                        [service-affecting]

**Watch out for.** Build the matrix. The pattern across sites names the
cause far faster than any single packet capture, and the matrix stays
useful as a living document, because the next firmware release will
change it.

**References:** [RFC 3947, NAT Traversal in
IKE](https://www.rfc-editor.org/rfc/rfc3947.html) · [RFC 3948, UDP
Encapsulation of ESP](https://www.rfc-editor.org/rfc/rfc3948.html) ·
[RFC 7383, IKEv2
Fragmentation](https://www.rfc-editor.org/rfc/rfc7383.html)

## Chapter 4. VPN and Remote Access

*Scenarios Q35 to Q41. Tier mix: 1 L1, 6 L2.*

### Orientation

A VPN builds an encrypted tunnel across an untrusted network. Two
flavours dominate:

**Site-to-site** connects two offices permanently. Neither end knows or
cares that a tunnel exists.

**Remote access** connects one user's device to the corporate network on
demand.

Whichever you are troubleshooting, remember this: a tunnel coming up
proves only that two devices authenticated to each other. It says
nothing about whether traffic can flow. Routing, DNS, policy and NAT all
still have to be right afterwards, and each one fails in its own way.

One of the most useful diagnostics in this chapter takes ten seconds.
**Test by IP, then test by name.** If IP works and name does not, you
have a DNS problem. If neither works, you have a routing or policy
problem. That single comparison eliminates half the possibilities before
you have opened a single config file.

### Scenarios in this chapter

  ---------------------------------------------------------------------------------------------------------------------------------------------------------
  ID                                                                                          Scenario                                           Tier
  ------------------------------------------------------------------------------------------- -------------------------------------------------- ----------
  [Q35](#q35.-a-remote-worker-connects-to-vpn-but-cant-access-internal-file-shares)           Connected but no access                            L2

  [Q36](#q36.-a-vpn-client-repeatedly-disconnects-at-about-the-same-interval)                 Repeating disconnect interval                      L2

  [Q37](#q37.-a-site-to-site-vpn-drops-whenever-large-file-transfers-start)                   Failure triggered by volume                        L2

  [Q38](#q38.-a-user-can-vpn-in-from-home-but-not-from-a-hotel-wi-fi)                         Venue network restriction                          L1

  [Q39](#q39.-after-a-vpn-concentrator-upgrade-users-get-certificate-not-trusted-errors)      Certificate chain problem                          L2

  [Q40](#q40.-split-tunnel-vpn-users-report-both-slow-internet-and-slow-internal-resources)   Tunnel policy and capacity                         L2

  [Q41](#q41.-a-remote-office-has-poor-vpn-performance-despite-a-good-local-speed-test)       Path performance                                   L2
  ---------------------------------------------------------------------------------------------------------------------------------------------------------

### Q35. A remote worker connects to VPN but can't access internal file shares

*Tier: L2. Safety: read-only.*

**Short answer.** Test by IP first, then by name. That tells you whether
you are chasing routing and policy or chasing DNS. Then verify the
tunnel routes include the file server subnet, the client received
internal DNS and the right search suffix, and the firewall permits SMB
from the VPN pool.

**What is actually going on.** The VPN establishing proves
authentication and tunnel setup succeeded. Nothing more. Four separate
things must also be true:

- A route for the file server subnet is pushed to the client
- Internal DNS is used for internal names, with the correct search
  suffix
- The firewall permits TCP 445 from the VPN address pool, which is often
  a separate zone with its own policy
- Kerberos can work, which needs the fully qualified name to match the
  service principal

That last point gives you a free diagnostic. Connecting by IP silently
falls back to NTLM and can succeed where connecting by name fails, so a
name-versus-IP difference here can mean DNS *or* Kerberos.

Interpreting the test:

  -----------------------------------------------------------------------
  Result                        Points at
  ----------------------------- -----------------------------------------
  IP works, name fails          DNS servers, search suffix, or Kerberos
                                SPN

  Neither works                 Routing or firewall policy

  Both work, authentication     Share permissions, SPN, or account issue
  fails                         
  -----------------------------------------------------------------------

**How to check**

    On the client, while connected                       [read-only]
      route print   /  ip route          is the server subnet routed?
      ipconfig /all                      internal DNS? search suffix?
      Get-DnsClientNrptPolicy            split DNS rules on Windows
      Get-NetIPInterface | sort InterfaceMetric
      resolvectl status                  per-link DNS on Linux

                                                         [active test]
      nslookup fileserver.corp.local <internal-dns-ip>
      Test-NetConnection fileserver -Port 445
      net use \\10.1.5.20\share          by IP, to isolate DNS

    On the firewall                                      [read-only]
      packet-tracer input outside tcp <vpn-pool-ip> 1234 <fileserver> 445 detailed

**Watch out for.** On Windows, the DNS Client service picks a resolver
based on interface metric and connection-specific suffix. A physical
adapter with a lower metric than the VPN adapter can win even when the
VPN pushed perfectly correct servers. Querying the internal DNS server
explicitly with `nslookup`` <name> <``dns-ip``>` bypasses that selection
logic and tells you whether the record exists at all.

**References:** [RFC 8598, Split DNS Configuration for
IKEv2](https://www.rfc-editor.org/rfc/rfc8598.html) · [RFC 4120,
Kerberos V5](https://www.rfc-editor.org/rfc/rfc4120.html)

### Q36. A VPN client repeatedly disconnects at about the same interval

*Tier: L2. Safety: read-only.*

**Short answer.** A repeating interval means something with a timer, but
draw the conclusion carefully. Under IKEv2 the peers do not negotiate a
common SA lifetime, so a "lifetime mismatch" is not by itself the fault.
Look instead for a rekey or reauthentication that is failing, an idle or
session limit, or NAT state expiring between the client and the head
end.

**What is actually going on.** This is a common interview trap, so get
it right.

In **IKEv1**, lifetimes are negotiated and the shorter value wins. In
**IKEv2**, RFC 7296 treats lifetime as a local matter. Each peer
enforces its own policy and the side with the shorter lifetime simply
initiates a rekey. Different lifetimes are normal and expected
behaviour.

So when an IKEv2 tunnel dies at a repeating interval, the interesting
question is why the rekey did not succeed:

- **The rekey exchange is being blocked.** A stateful device between the
  peers dropped the UDP 4500 mapping, so the exchange never completes.
- **Reauthentication is failing.** Some implementations require full
  reauthentication rather than a simple rekey, and that fails if a
  credential or certificate is no longer valid.
- **An idle or session timeout is enforced** by the head end group
  policy, independent of crypto.
- **NAT keepalive is too infrequent** for the NAT device's idle timeout,
  so the mapping is lost mid-session.
- **An implementation defect** in one peer's rekey handling, which is
  why firmware version matters.

**How to check**

                                                         [read-only]
    show crypto ikev2 sa detail          life and remaining time, status
    show crypto ipsec sa | include lifetime|sa timing
    show run | include lifetime|keepalive|idle
    show logging | include IKEV2|REKEY|RETRANSMIT|DELETE

    Compare on both peers
      IKE SA lifetime and reauth setting
      IPsec SA lifetime
      DPD interval and retry
      NAT keepalive interval vs the NAT device idle timeout
      group-policy vpn-idle-timeout and vpn-session-timeout

                                                         [active test]
    tcpdump -n 'udp port 4500'           does the rekey exchange happen at all?

**Watch out for.** Get exact timestamps before theorising. A failure at
a precise 3600 seconds points at a crypto lifetime and a failed rekey. A
fuzzy "about an hour" points at an idle timeout or upstream instability.
Those need different fixes and the difference is only visible in the
numbers.

**Reference:** [RFC 7296,
IKEv2](https://www.rfc-editor.org/rfc/rfc7296.html)

### Q37. A site-to-site VPN drops whenever large file transfers start

*Tier: L2. Safety: read-only.*

**Short answer.** Separate "the transfer stalls" from "the tunnel
actually drops," because they have different causes. Fragmentation and
MTU problems usually stall or degrade the transfer while the SA stays
up. If the SA genuinely goes down, look at volume-based lifetimes,
crypto engine exhaustion, and anti-replay.

**What is actually going on.** Ask the first question properly: did the
tunnel drop, or did the transfer fail while the tunnel stayed up? The
answer changes everything.

**If the transfer stalls and the SA stays up**, you are almost certainly
looking at MTU. IPsec adds roughly 50 to 70 bytes depending on mode,
cipher, and whether NAT-T is in use. GRE adds 24 more. A 1500-byte
payload becomes an oversized packet that must fragment or be dropped,
and with ICMP filtered the sender never learns.

**If the SA genuinely drops during bulk transfer**, consider these
instead:

- **Volume-based lifetime.** IPsec SAs can be limited by kilobytes
  transferred as well as by time. A large transfer hits the volume limit
  and triggers a rekey. If that rekey fails, the tunnel drops, and it
  will look like the transfer caused it because it did.
- **Crypto engine or CPU exhaustion.** Software crypto on an undersized
  platform saturates under sustained throughput.
- **Packet-per-second limits** on the platform or a middlebox.
- **Anti-replay window drops.** High rates plus QoS reordering can push
  packets outside the replay window, which shows in the SA counters.

**How to check**

                                                         [read-only]
    show crypto ipsec sa | include lifetime|kilobytes|replay|frag
    show crypto ipsec sa | include encaps|decaps
    show crypto engine accelerator statistic
    show processes cpu sorted
    show logging | include REKEY|REPLAY|IPSEC

                                                         [active test]
    ping <far-end> size 1500 df-bit      then bisect downward
    Fix, on the tunnel interface, both ends              [change approval]
      interface Tunnel0
        ip mtu 1400
        ip tcp adjust-mss 1360

    Typical overheads
      GRE                    24 bytes
      IPsec ESP tunnel mode  roughly 50 to 60 bytes
      NAT-T (UDP 4500)       plus 8 bytes

**Watch out for.** MSS clamping helps TCP only. UDP traffic over the
same tunnel still needs a lower MTU or working PMTUD. Clamping adjusts
one TCP option; it is not a general MTU fix, and 1360 is not a magic
number.

**References:** [RFC 4459, MTU and Fragmentation Issues with
Tunnels](https://www.rfc-editor.org/rfc/rfc4459.html) · [RFC 4303, IP
Encapsulating Security
Payload](https://www.rfc-editor.org/rfc/rfc4303.html)

### Q38. A user can VPN in from home but not from a hotel Wi-Fi

*Tier: L1. Safety: active test.*

**Short answer.** The venue network is filtering or intercepting
something. Check for a captive portal first, then test whether the VPN's
ports are usable, then fall back to a TLS-based VPN profile on TCP 443
or a phone hotspot.

**What is actually going on.** Guest and hospitality networks commonly
permit very little outbound. IKE on UDP 500 and 4500 is a frequent
casualty. Captive portals intercept everything until the user
authenticates in a browser, and a VPN client that starts before the
portal is satisfied fails in a way that looks like a server problem.

TCP 443 usually works, and that is why most vendors offer a TLS
fallback. But do not claim that 443 always works, because it does not.
Networks block or break VPN over 443 using authenticated proxies, TLS
inspection, SNI-based policy, and application identification. Corporate
guest networks and some national networks do this deliberately.

Double NAT and carrier-grade NAT are worth testing but are not
automatically fatal. Standards-compliant NAT traversal is designed to
cope with them. Treat them as hypotheses.

**How to check**

                                                        # [active test]
    curl -I http://neverssl.com          # a forced redirect means captive portal
    nc -vz <vpn-head-end> 443            # TCP handshake, this one is meaningful
    traceroute <vpn-head-end>
    A caution about testing UDP
      nc -vz -u <host> 500 does NOT prove reachability.
      UDP has no handshake, so nc reports success unless an ICMP port
      unreachable comes back. Absence of an error is not evidence of a path.
      To test UDP properly, send something the far end will answer, or
      capture at both ends and compare.

**Watch out for.** This is a very common L1 ticket and the good answer
is short and decisive. Confirm it is the venue network, move the user to
the TLS profile or a hotspot, and move on. Spending an hour on someone
else's hotel Wi-Fi is the wrong call.

**References:** [RFC 8952, Captive Portal
Architecture](https://www.rfc-editor.org/rfc/rfc8952.html) · [RFC 3948,
UDP Encapsulation of ESP](https://www.rfc-editor.org/rfc/rfc3948.html)

### Q39. After a VPN concentrator upgrade, users get "certificate not trusted" errors

*Tier: L2. Safety: read-only.*

**Short answer.** The certificate now being presented does not chain to
a CA the clients trust. Usually the appliance fell back to a self-signed
certificate, or the intermediate CA certificate was not installed
alongside the server certificate.

**What is actually going on.** A client validates a chain, not a single
certificate. The server must present its own certificate *and* every
intermediate up to a root the client already trusts.

Appliances often revert to a self-signed certificate after a firmware
upgrade or a config restore. Administrators frequently import the server
certificate and omit the intermediate, which works on machines that
happen to have cached that intermediate and fails everywhere else. That
is where the maddening "works on my laptop" pattern comes from.

Two related causes look similar but produce different error text: a
Subject Alternative Name list that omits the hostname users actually
type, and a simple expiry.

**How to check**

                                                        # [active test]
    openssl s_client -connect vpn.example.com:443 -showcerts

    # Read the returned chain. Server certificate, then intermediates.
    # The verify result names the fault directly:
    #   "self signed certificate"
    #   "unable to get local issuer certificate"  = missing intermediate

    openssl x509 -in server.crt -noout -text | grep -A1 "Subject Alternative Name"
    openssl x509 -in server.crt -noout -dates
    Fix                                                  [change approval]
      - install the full chain, server plus intermediates
      - confirm the SAN covers every hostname clients use
      - push the issuing root to clients via GPO or MDM if it is a private CA

**Watch out for.** `openssl`` ``s_client`` -``showcerts` answers this by
printing exactly what the server sends. If only one certificate comes
back and it is not self-signed, the intermediate is missing. Nothing
more is needed to confirm it.

**References:** [RFC 5280, X.509 Certificate
Profile](https://www.rfc-editor.org/rfc/rfc5280.html) · [RFC 6125,
Service Identity
Verification](https://www.rfc-editor.org/rfc/rfc6125.html)

### Q40. Split-tunnel VPN users report both slow internet and slow internal resources

*Tier: L2. Safety: read-only.*

**Short answer.** Both symptoms sharing one cause is the clue. The
split-tunnel policy is probably not being applied, so all traffic
including web browsing is going through the concentrator and saturating
it. Check the routes pushed to the client, then the concentrator's load.

**What is actually going on.** Split tunnelling sends only corporate
subnets through the VPN and lets everything else go direct. When that
fails, whether from the wrong group policy being applied, an included
subnet of 0.0.0.0/0, or a client profile overriding the server setting,
every user's video calls, streaming and software updates traverse the
concentrator.

The device saturates, internal traffic queues behind internet traffic,
and both degrade together.

In a deliberate full-tunnel design this is expected behaviour and the
answer becomes capacity: the concentrator and its circuit must be sized
for total user internet demand, not just corporate traffic.

**How to check**

    On the client                                        [read-only]
      route print | find "0.0.0.0"     is the default route via the tunnel?
      ipconfig /all

                                                         [active test]
      tracert 8.8.8.8                  is hop 1 the concentrator?

    On the concentrator                                  [read-only]
      show vpn-sessiondb detail anyconnect
      show cpu usage ; show traffic
      show run all group-policy <name> | include split
      show run tunnel-group <name>

**Watch out for.** A traceroute to a public address settles this in
seconds. If the first hop is the concentrator, split tunnelling is not
in effect, whatever the configuration claims it is doing.

**Reference:** [RFC 7296,
IKEv2](https://www.rfc-editor.org/rfc/rfc7296.html)

### Q41. A remote office has poor VPN performance despite a good local speed test

*Tier: L2. Safety: active test.*

**Short answer.** The speed test measured the path to a nearby test
server, not the path to your head end. Suspect congestion or peering on
that specific route, or asymmetric routing. Run MTR from both directions
and compare against a control site.

**What is actually going on.** A fast result against a well-peered local
server proves the access circuit is healthy. It proves nothing about the
transit path to a head end several hundred kilometres away.

Poor performance on one path usually means congestion at a peering
point, a saturated transit link, or a route taking an unexpected detour.

Latency also interacts badly with TCP over a tunnel. Throughput is
bounded by window size divided by round trip time, so an extra 60 ms can
halve throughput with zero packet loss. That is how a "good" 100 Mbps
speed test coexists with 8 Mbps through the tunnel.

**How to check**

                                                        # [active test]
    mtr -rwzc 200 <vpn-head-end>       # from the branch
    mtr -rwzc 200 <branch-public-ip>   # from the head end, same window
    iperf3 -c <internal-server> -t 30
    iperf3 -c <internal-server> -t 30 -R   # reverse direction
    ping -c 100 <head-end>                 # jitter and loss baseline
    How to read it
      Loss at one hop that persists downstream  ->  real loss at that hop
      Loss at one hop that clears afterwards    ->  ICMP rate limit, ignore it
      Asymmetric latency between the two MTRs   ->  asymmetric path
      Throughput far below bandwidth-delay      ->  window or latency limited

**Watch out for.** Loss shown at a single intermediate hop that
disappears at later hops is a control-plane rate limit, not a fault.
Misreading that is one of the most common false escalations to a
carrier.

For structured throughput testing use RFC 6349, which is designed for
live paths. Do not reach for RFC 2544 methods here. Those are laboratory
benchmarks and RFC 6815 explains why running them on a production
network is harmful.

**References:** [RFC 6349, TCP Throughput
Testing](https://www.rfc-editor.org/rfc/rfc6349.html) · [RFC 6815, RFC
2544 on Production Networks Considered
Harmful](https://www.rfc-editor.org/rfc/rfc6815.html)

## Chapter 5. Wireless

*Scenarios Q42 to Q49. Tier mix: 2 L1, 6 L2.*

### Orientation

Wireless breaks people's mental models because it behaves nothing like a
switch port.

**It is a shared, half-duplex medium.** Every device on a radio takes
turns. Twenty clients on one access point are sharing one conversation,
not getting twenty dedicated connections. The "1.2 Gbps" on the box is
an aggregate theoretical maximum, not what any one user gets.

**Signal strength alone tells you very little.** What matters is
signal-to-noise ratio and the retry rate. A client with a strong signal
in a noisy room performs worse than a client with a moderate signal in a
quiet one.

**The client decides where to connect, not you.** The standard gives the
access point no authority to move a client. You can influence the
decision with power levels and standards like 802.11k and 802.11v, but
you cannot command it.

Two numbers worth memorising, because they turn vague complaints into
measurable facts:

- **RSSI better than -67 dBm** for voice, -70 dBm for data
- **SNR of 25 dB or better**, and **retries under 10 to 15 percent**

### Scenarios in this chapter

  --------------------------------------------------------------------------------------------------------------------------------------------------------
  ID                                                                                        Scenario                                            Tier
  ----------------------------------------------------------------------------------------- --------------------------------------------------- ----------
  [Q42](#q42.-users-experience-random-wi-fi-disconnects-only-in-one-area-of-the-building)   Localised disconnects                               L2

  [Q43](#q43.-a-new-ap-was-added-but-clients-still-connect-to-a-farther-weaker-ap)          Sticky client roaming                               L2

  [Q44](#q44.-wireless-throughput-is-much-lower-than-wired-for-the-same-user)               Expected vs faulty performance                      L1

  [Q45](#q45.-guest-wi-fi-users-can-access-internal-vlans-unexpectedly)                     Segmentation failure                                L2

  [Q46](#q46.-certain-iot-devices-fail-to-connect-to-a-wpa2-enterprise-ssid)                802.1X and embedded devices                         L2

  [Q47](#q47.-after-a-wireless-controller-firmware-update-multiple-aps-go-offline)          AP join failure                                     L2

  [Q48](#q48.-users-near-the-kitchen-experience-2.4-ghz-wi-fi-dropouts)                     Non-Wi-Fi interference                              L1

  [Q49](#q49.-wi-fi-calling-quality-is-choppy-while-data-works-fine)                        Carrier Wi-Fi calling                               L2
  --------------------------------------------------------------------------------------------------------------------------------------------------------

### Q42. Users experience random Wi-Fi disconnects only in one area of the building

*Tier: L2. Safety: read-only.*

**Short answer.** A location-bound symptom narrows things down, but do
not jump straight to RF. Check the serving AP's own health first:
uplink, switchport, PoE, and whether it is rebooting. Then, if the
infrastructure is clean, classify the RF problem.

**What is actually going on.** It is tempting to say a fault affecting
one area must be RF. That reasoning is wrong, and it sends people
surveying with a spectrum analyser when the actual cause was a failing
PoE injector.

Faults that are location-bound but not RF at all:

- The AP's uplink switchport is flapping or erroring
- PoE budget exhaustion, so the AP resets under load
- A cable run to that AP is damaged
- The AP itself is failing, or rebooting on a watchdog
- That AP has different configuration, a different tag or group, or a
  stale image

Once infrastructure is ruled out, the RF causes split three ways, and
they need opposite remedies:

  -----------------------------------------------------------------------
  RF cause        Signature               Remedy
  --------------- ----------------------- -------------------------------
  Coverage hole   Low RSSI, clients drop  Add or reposition an AP
                  when moving             

  Co-channel      Good RSSI, high channel Change channel plan, reduce
  interference    utilisation             power

  Non-Wi-Fi       Good RSSI, high         Find and remove the emitter, or
  interference    retries, high noise     move to another band
                  floor                   
  -----------------------------------------------------------------------

**How to check**

    Infrastructure first                                 [read-only]
      show ap uptime <ap-name>            has it been rebooting?
      show interface <ap-switchport> | include error|flap|rate
      show power inline <ap-switchport>
      show logging | include <ap-name>

    Then RF                                              [read-only]
      show ap auto-rf <ap-name>           channel, power, noise, interference
      show client detail <mac>            RSSI, SNR, retries, data rate
      show ap dot11 5ghz summary          channel utilisation

    Targets
      RSSI  better than -67 dBm (voice) / -70 dBm (data)
      SNR   25 dB or better
      Retries under 10 to 15 percent
      Channel utilisation under 40 percent

**Watch out for.** Good RSSI with high retries means noise, not
coverage. Adding another AP in that situation makes things worse by
adding another contender for airtime. That distinction is the difference
between fixing the problem and spending money to amplify it.

**Reference:** [IEEE
802.11](https://standards.ieee.org/ieee/802.11/7028/)

### Q43. A new AP was added but clients still connect to a farther, weaker AP

*Tier: L2. Safety: read-only.*

**Short answer.** Sticky client behaviour. Roaming is the client's
decision, and most clients hold their association until the signal
becomes unusable. Size the cells properly with transmit power, then use
802.11k and 802.11v to influence the decision.

**What is actually going on.** The 802.11 standard gives the AP no
authority to move a client. The client scans and decides, and vendor
implementations vary enormously in how eager that decision is.

Oversized cells make it worse. If the old AP is still audible at -75
dBm, the client sees no reason to move, even though throughput at that
signal level is a fraction of what the new AP would give it. Lowering
transmit power shrinks the cell and forces the decision sooner.

The relevant amendments: **802.11k** gives the client a neighbour report
so it scans efficiently. **802.11v** lets the infrastructure suggest a
transition. **802.11r** speeds up the handoff once the client agrees to
move.

**How to check**

                                                         [read-only]
    show client detail <mac>            associated AP, RSSI, data rate
    show ap auto-rf <ap-name>           Tx power level, neighbour list
    show wlan <id>                      are 11k, 11v and 11r enabled?
    Levers, in order of preference                       [change approval]
      1. Reduce Tx power so cells overlap about 15 to 20 percent, not more
      2. Enable 802.11k neighbour reports and 802.11v BSS transition
      3. Enable 802.11r fast transition for voice clients
      4. Disable the lowest legacy data rates (1, 2, 5.5, 11 Mbps)
      5. RSSI-based client steering, as a last resort

**Watch out for.** Disabling low legacy data rates is the most
under-used lever here. It shrinks the effective cell edge, forces
earlier roaming, and reclaims airtime that slow clients would otherwise
consume. No hardware required. Check for legacy devices that genuinely
need those rates before you do it.

**Reference:** [IEEE 802.11k, 802.11v, 802.11r
amendments](https://standards.ieee.org/ieee/802.11/7028/)

### Q44. Wireless throughput is much lower than wired for the same user

*Tier: L1. Safety: read-only.*

**Short answer.** Check the negotiated PHY rate and band, channel width,
channel utilisation, how many clients share that radio, and the AP's
uplink capacity. Then establish whether this is a fault at all, because
a large gap between wired and wireless is normal.

**What is actually going on.** Several multipliers stack up:

- A client on 2.4 GHz with a 20 MHz channel and one spatial stream is
  capped far below a 5 GHz client on 80 MHz with two streams
- Airtime is shared, so twenty active clients each get a slice
- Legacy clients at low data rates consume disproportionate airtime for
  the same bytes, degrading everyone
- An AP with a 1 Gbps uplink serving radios capable of more in aggregate
  is itself the bottleneck

Real TCP throughput of 40 to 60 percent of the negotiated PHY rate is
normal, not a fault.

**How to check**

                                                         [read-only]
    show client detail <mac>
      -> data rate, spatial streams, channel width, band, RSSI, SNR
    show ap dot11 5ghz summary
      -> client count and channel utilisation per radio
    show interface <ap-uplink> | include rate

**Watch out for.** Ask what the user is comparing against. "Slower than
wired" is expected physics and not a ticket. "Slower than it was last
week, same laptop, same seat" is a real change and worth your time.
Establishing which one you have should be your first question, not your
last.

**Reference:** [IEEE 802.11ac /
802.11ax](https://standards.ieee.org/ieee/802.11/7028/)

### Q45. Guest Wi-Fi users can access internal VLANs unexpectedly

*Tier: L2. Safety: read-only.*

**Short answer.** Segmentation has failed somewhere along a chain, and
VLAN mapping is only one of the links. Establish what address the guest
client actually received and what it can reach, then work back through
the chain. Treat it as a security incident from the start.

**What is actually going on.** Guest isolation depends on several
controls in series, and any one of them failing produces the same
result:

- **SSID to VLAN or policy mapping** on the controller or AP group is
  wrong
- **Switchport configuration** carrying AP traffic has a wrong native
  VLAN or allowed list, so untagged frames land in an internal VLAN
- **Firewall or ACL policy** between the guest segment and internal
  segments is missing, too broad, or was never written because everyone
  assumed the VLAN was enough
- **VRF or routing leak**, where the guest subnet is reachable through a
  route it should not have
- **Guest anchor tunnel failure**, so traffic is switched locally at the
  AP instead of being tunnelled to the anchor controller in the DMZ
- **Policy or role tag error**, where the client is assigned the wrong
  role after authentication

Client isolation within the SSID stops guest-to-guest traffic and does
nothing at all about guest-to-internal, which is a distinction people
get wrong under pressure.

**How to check**

    Start from the client                                [active test]
      ipconfig /all                      which subnet was actually issued?
      ping <internal gateway>
      tracert <internal host>            which way does it go?

    Then work back                                       [read-only]
      show wlan <id>                     interface, VLAN, policy mapping
      show ap config general <ap-name>   AP group, local switching VLAN map
      show interface <ap-switchport> trunk    native VLAN, allowed VLANs
      show mobility anchor                    is the anchor tunnel up?
      show ip route <guest-subnet>            VRF leak?
      Firewall: policy from guest zone to internal zones

**Watch out for.** Raise this through the security incident process, not
the routine change queue. Segmentation failure on a guest network is a
reportable control failure under most compliance regimes, and treating
it as business as usual is the wrong instinct.

**References:** [IEEE
802.1Q](https://standards.ieee.org/ieee/802.1Q/10323/) · [NIST SP
800-153, Securing WLANs](https://csrc.nist.gov/pubs/sp/800/153/final)

### Q46. Certain IoT devices fail to connect to a WPA2-Enterprise SSID

*Tier: L2. Safety: read-only.*

**Short answer.** The devices probably do not implement 802.1X, or
implement only an EAP method your RADIUS server is not offering. Give
them a dedicated SSID and VLAN with a strong PSK or MAC authentication,
then compensate for the weaker authentication with segmentation.

**What is actually going on.** WPA2-Enterprise needs a working
supplicant, a trusted CA certificate, and a supported EAP method. Cheap
or embedded devices often have none of those.

Common failure modes: no supplicant at all; support for PEAP-MSCHAPv2
only when the server requires EAP-TLS; certificate validation failing
because the device has no trust store and no way to install one; and no
real-time clock, so certificate validity checks fail on every boot until
NTP syncs.

Forcing these devices onto enterprise authentication is not achievable.
The correct answer is a design change.

**How to check**

    ISE or RADIUS                                        [read-only]
      Live Logs, filtered by device MAC
        "EAP method not supported"
        "certificate not trusted"
        "no supplicant response"
      Each names a different fix.

    Controller                                           [service-affecting]
      debug client <mac>
      show client detail <mac>           does it reach EAP at all?
    Design                                               [change approval]
      Separate IoT SSID and VLAN
      WPA2-PSK with a unique key, or MAB with a device profile
      Deny IoT VLAN to internal VLANs by default
      Permit only the specific flows the devices actually need

**Watch out for.** Say out loud that MAC authentication is weak because
MAC addresses are trivially spoofed, and that the compensating control
is segmentation rather than the authentication itself. Interviewers are
listening for whether you know you are accepting a risk deliberately or
by accident.

**References:** [IEEE
802.1X](https://standards.ieee.org/ieee/802.1X/7345/) · [RFC 5216,
EAP-TLS](https://www.rfc-editor.org/rfc/rfc5216.html) · [NIST SP
800-213, IoT Device
Cybersecurity](https://csrc.nist.gov/pubs/sp/800/213/final)

### Q47. After a wireless controller firmware update, multiple APs go offline

*Tier: L2. Safety: read-only.*

**Short answer.** The APs cannot rejoin. Read the join statistics,
because the controller records the specific reason. Usual causes are an
AP model dropped from the new release, a CAPWAP control-plane problem,
or certificate validation failing.

**What is actually going on.** APs download their image from the
controller and rejoin after an upgrade, so a model that was dropped from
the new release simply never comes back.

CAPWAP needs UDP 5246 for control and 5247 for data. A firewall rule or
ACL that the old release tolerated can break the new one if discovery
behaviour changed.

Certificate errors are common on older hardware whose
manufacturer-installed certificates have expired, and on controllers
whose clock is wrong, because certificate validation is time-sensitive.
Check the clock before you blame the certificates.

**How to check**

    Controller                                           [read-only]
      show ap join stats summary all
      show ap join stats detailed <ap-mac>     names the failure reason
      show ap image all                        predownload status per model
      show time                                clock correct?

    AP console                                           [service-affecting]
      debug capwap client events
      debug pm pki enable                      certificate validation detail

    Network                                              [read-only]
      Is UDP 5246 and 5247 permitted AP to controller?
      Is discovery working: DHCP option 43, DNS, or broadcast?

**Watch out for.** Check the release notes for supported AP models
*before* the upgrade window, and stage the upgrade on one AP first.
Describing that as your standard practice answers the process half of
this question, which is usually what is really being probed.

**Reference:** [RFC 5415, CAPWAP Protocol
Specification](https://www.rfc-editor.org/rfc/rfc5415.html)

### Q48. Users near the kitchen experience 2.4 GHz Wi-Fi dropouts

*Tier: L1. Safety: read-only.*

**Short answer.** Interference from the microwave oven, which emits
around 2.45 GHz and sits on top of the upper 2.4 GHz Wi-Fi channels.
Move clients to 5 GHz, or shift the nearby AP to a channel further from
the emitter.

**What is actually going on.** Microwave leakage raises the noise floor
for the length of a cooking cycle. The symptom is intermittent and
correlates with lunchtime rather than with network load, which is a
useful thing to notice.

Wi-Fi cannot negotiate with a non-Wi-Fi emitter. It defers or suffers
corruption, which shows up as retries and dropped associations. The 2.4
GHz band offers only three non-overlapping 20 MHz channels, so your
avoidance options are limited. Moving clients to 5 GHz is the durable
fix.

**How to check**

                                                         [read-only]
    show ap auto-rf <ap-name>          interference and noise per channel

    Spectrum analysis (CleanAir, Ekahau, Chanalyzer)
      Microwave signatures are broad and vary over time.
      They look nothing like a Wi-Fi transmission.
    Actions                                              [change approval]
      1. Confirm the timing correlates with kitchen use
      2. Move that AP to channel 1, furthest from about 2.45 GHz
      3. Enable band steering; check 5 GHz coverage is adequate there
      4. Do not disable 2.4 GHz entirely if legacy or IoT clients need it

**Watch out for.** A packet capture cannot see a microwave oven at all,
because the energy is not a decodable frame. Only spectrum analysis
distinguishes non-Wi-Fi interference from co-channel Wi-Fi contention,
and those need opposite remedies.

**References:** [IEEE
802.11](https://standards.ieee.org/ieee/802.11/7028/) · [ITU-R Radio
Regulations](https://www.itu.int/pub/R-REG-RR)

### Q49. Wi-Fi calling quality is choppy while data works fine

*Tier: L2. Safety: read-only.*

**Short answer.** First establish which kind of Wi-Fi calling you are
dealing with, because the answer changes completely. Carrier Wi-Fi
calling is encrypted to the mobile operator's gateway and your WLAN
cannot see the voice inside it. Enterprise softphone traffic is a
different problem entirely.

**What is actually going on.** This scenario is commonly answered
wrongly.

**Carrier Wi-Fi calling** (the feature built into a mobile handset)
establishes an IPsec tunnel from the phone to the operator's evolved
packet data gateway. Everything inside is encrypted. Your WLAN sees ESP
or UDP 4500 to an internet destination, not RTP, and it cannot read or
trust any inner DSCP marking. Marking the outer packet is possible in
principle but the phone chooses it, not you.

That means the levers available to you are:

- **WMM and airtime**, which apply to the encrypted flow just as they do
  to anything else
- **RF quality**, since retries add jitter regardless of what is inside
  the packet
- **Roaming delay**, which is audible on a call and invisible on data
- **The internet path** to the operator gateway, including latency and
  loss
- **Reachability of the operator gateway**, since some firewalls block
  IKE and ESP outbound
- **Whether your guest or corporate policy permits IPsec outbound at
  all**

**Enterprise voice over WLAN**, meaning a softphone or a Wi-Fi handset
on your own call platform, is the case where end-to-end DSCP EF and a
trusted QoS boundary genuinely apply. See
[Q75](#q75.-voip-quality-complaints-only-come-from-wireless-users-not-wired-ones)
for that one.

**How to check**

    Identify the traffic first                           [active test]
      Capture at the AP or switchport for the client.
      ESP or UDP 4500 to an operator address = carrier Wi-Fi calling.
      RTP on 16384-32768 to your call platform = enterprise voice.

    Then, for carrier Wi-Fi calling                      [read-only]
      show client detail <mac>       retries, data rate, RSSI, SNR
      show ap auto-rf <ap-name>      channel utilisation
      show wlan <id> | include WMM|Fast Transition
      Firewall: is UDP 500 and 4500 permitted outbound from that SSID?
      Path quality to the operator gateway: latency, jitter, loss

**Watch out for.** If someone tells you to "trust DSCP EF end to end"
for carrier Wi-Fi calling, they are describing a different problem. You
cannot mark what you cannot see. Many candidates give the enterprise
VoIP answer to both questions, so make the distinction explicitly.

**References:** [RFC 7296,
IKEv2](https://www.rfc-editor.org/rfc/rfc7296.html) · [RFC 8325, Mapping
DiffServ to 802.11](https://www.rfc-editor.org/rfc/rfc8325.html) · [IEEE
802.11e / WMM](https://standards.ieee.org/ieee/802.11/7028/)

# Part III. NOC Operations

Technical skill gets you shortlisted. Working an incident without making
it worse gets you hired. Part III covers alerting, prioritisation,
escalation, handover and documentation: the operational judgement that
interviewers test at every tier.

## Chapter 6. Monitoring, Alerting and NOC Process

*Scenarios Q50 to Q64. Tier mix: 6 L1, 9 L2.*

### Orientation

This is the chapter people skip, and it is the chapter that gets them
hired.

Technical skill gets you shortlisted. What separates two technically
similar candidates is whether they can work an incident without making
it worse: prioritising sensibly, escalating at the right moment, handing
over cleanly, and writing something afterwards that helps the next
person.

A few terms you will hear constantly:

- **P1 to P4.** Incident priority, usually derived from business impact
  and urgency together. A P1 is a major outage. A P4 is a single user
  with a minor problem.
- **SLA.** The contractual time you have to respond and resolve. Missing
  one has commercial consequences, which is why escalation timing
  matters.
- **RCA.** Root cause analysis, written after the fact.
- **CAB.** Change Advisory Board, the group that approves changes.
- **Runbook.** The documented procedure for a known scenario.

If you have never worked in a NOC, read this chapter twice. The
scenarios describe how the job actually feels on a night shift, and
interviewers can tell within one answer whether you have thought about
it.

### Scenarios in this chapter

  -------------------------------------------------------------------------------------------------------------------------------------------------------
  ID                                                                                        Scenario                                           Tier
  ----------------------------------------------------------------------------------------- -------------------------------------------------- ----------
  [Q50](#q50.-monitoring-floods-with-hundreds-of-alerts-during-a-single-outage)             Alert storm                                        L1

  [Q51](#q51.-a-critical-alert-didnt-page-anyone-during-last-nights-outage)                 Alerting pipeline failure                          L2

  [Q52](#q52.-a-flapping-interface-downup-alert-every-5-minutes-on-a-core-switch)           Alert noise vs real fault                          L2

  [Q53](#q53.-ticket-volume-for-the-same-issue-is-coming-in-from-multiple-sites)            Major incident handling                            L1

  [Q54](#q54.-monitoring-shows-100-packet-loss-to-a-device-users-say-is-working-fine)       Monitoring path vs user path                       L1

  [Q55](#q55.-how-do-you-decide-whether-to-escalate-or-keep-troubleshooting)                Escalation judgement                               L1

  [Q56](#q56.-a-maintenance-window-causes-unexpected-alerts-to-page-on-call-staff)          Suppression                                        L1

  [Q57](#q57.-how-do-you-document-a-resolved-incident-for-future-reference)                 Knowledge management                               L1

  [Q58](#q58.-bandwidth-graphs-show-a-steady-climb-toward-saturation-on-a-wan-link)         Capacity management                                L2

  [Q59](#q59.-a-p1-ticket-sits-untouched-for-20-minutes-because-the-engineer-is-on-break)   Escalation automation                              L2

  [Q60](#q60.-multiple-monitoring-tools-report-the-same-outage-at-different-severities)     Reconciling tool disagreement                      L2

  [Q61](#q61.-youve-fixed-an-issue-but-the-dashboard-still-shows-red)                       Verification                                       L2

  [Q62](#q62.-another-teams-change-caused-an-outage-and-the-noc-wasnt-told)                 Change visibility                                  L2

  [Q63](#q63.-your-shift-is-ending-but-an-incident-isnt-resolved)                           Handover                                           L2

  [Q64](#q64.-configuration-drift-is-causing-repeat-incidents-across-similar-devices)       Telemetry and automation                           L2
  -------------------------------------------------------------------------------------------------------------------------------------------------------

### Q50. Monitoring floods with hundreds of alerts during a single outage

*Tier: L1. Safety: read-only.*

**Short answer.** Find the root-cause alert, which is usually the
highest device in the dependency tree that went down, and treat the rest
as symptoms. Raise one parent incident, link the children to it, and
work the parent.

**What is actually going on.** Most monitoring systems poll each device
independently, so a single core switch failure alerts on everything
behind it. Without dependency mapping the platform cannot tell cause
from consequence.

The technique is to sort by timestamp and map the alerting devices onto
the topology. The first alert, on the device closest to the core, is
usually the cause. Everything behind it that alerted afterwards is a
symptom.

**How to work it**

      1. Sort by first-occurrence timestamp, not by severity
      2. Map the alerting devices onto the topology
      3. Identify the highest common upstream device
      4. Open one parent incident; link children to it
      5. Communicate once, from the parent
      6. Afterwards: configure dependency suppression so this is automatic

**Watch out for.** The recovery pattern confirms your diagnosis. Fix the
root cause and the downstream alerts clear on their own within a poll
cycle or two. If they do not, you had more than one fault, and that is
worth knowing before you close anything.

**Reference:** [ITIL 4 Incident
Management](https://www.axelos.com/certifications/itil-service-management)

### Q51. A critical alert didn't page anyone during last night's outage

*Tier: L2. Safety: read-only.*

**Short answer.** Walk the alerting chain end to end. Each stage fails
differently and only the audit trail tells you which one broke.

**What is actually going on.** The pipeline has more independent failure
points than people expect, and every one produces the same outcome:

- The check did not exist for that condition
- The threshold was set too high, so it never fired
- A suppression or maintenance window was still active from an earlier
  change
- Severity mapping placed it below paging level
- The routing rule matched a team or schedule with a gap
- The on-call schedule had nobody assigned at that moment
- The notification was generated and delivery failed: expired
  integration key, SMS gateway problem, phone in do-not-disturb

**How to work it**

    Confirm each stage in order                          [read-only]
      [ ] Check existed and was enabled for that device or service
      [ ] Condition breached the configured threshold
      [ ] No suppression or maintenance window was active
      [ ] Severity mapping placed it at paging level
      [ ] Routing rule matched and selected an escalation policy
      [ ] Someone was on call at that exact moment
      [ ] Notification was generated (platform audit log)
      [ ] Notification was delivered and acknowledged

    Then
      - fix the specific stage that failed
      - add a synthetic end-to-end alert test to the monthly routine

**Watch out for.** Schedule gaps at shift handover and around public
holidays are the most common cause and the easiest to miss, because the
schedule looks fine when you check it during working hours. Check it as
it was at the time of the outage, not as it is now.

**Reference:** [Google SRE Workbook, Alerting on
SLOs](https://sre.google/workbook/alerting-on-slos/)

### Q52. A flapping "interface down/up" alert every 5 minutes on a core switch

*Tier: L2. Safety: read-only.*

**Short answer.** Investigate the physical cause first. Only after
confirming the flap is genuinely not affecting service should you dampen
the alert, and on a core device dampening should never be your first
action.

**What is actually going on.** A repeating five-minute interval suggests
a timer somewhere: a device rebooting on a watchdog, a PoE device
power-cycling, a failing optic crossing a thermal threshold, or a
negotiation loop. Cable faults usually flap irregularly.

The whole point of this question is whether you can tell "suppress the
noise" apart from "fix the fault." On core infrastructure, suppressing
an alert is how a genuine failure gets missed three weeks later.

**How to check**

                                                         [read-only]
    show interface <if> | include flap|last input|reset|error
    show logging | include <if>
    show interface transceiver detail    Rx power drifting toward threshold?
    show power inline <if>               PoE device cycling?
    show interface <if> counters errors
    Only after confirming it is not service-affecting    [change approval]
      interface <if>
        carrier-delay msec 2000
      In the monitoring tool: raise the flap-count threshold.
      Do not disable the check.

**Watch out for.** `show interface transceiver detail` catching an Rx
power reading drifting toward the low-warning threshold predicts an
optic failure before it becomes an outage. Bringing that up unprompted
signals real operational maturity.

**Reference:** [RFC 2863, Interfaces Group
MIB](https://www.rfc-editor.org/rfc/rfc2863.html)

### Q53. Ticket volume for the same issue is coming in from multiple sites

*Tier: L1. Safety: read-only.*

**Short answer.** Declare a major incident, make one ticket the parent,
link the rest, publish a single status update, and investigate the
common upstream element that all affected sites share.

**What is actually going on.** Multiple sites reporting at once implies
a shared dependency: a common transit provider, a central DNS or
authentication service, a data centre, a cloud region, or a change
pushed everywhere simultaneously.

Working the tickets individually duplicates effort, produces
contradictory updates to different customers, and delays finding the
shared cause.

**How to work it**

      1. Declare major incident; assign an incident manager
      2. Parent ticket created; inbound tickets linked as children
      3. Build the affected AND unaffected site list
           What do affected sites share that unaffected sites do not?
      4. Check the change calendar for the previous 24 hours
      5. Check upstream provider status pages
      6. One channel, one cadence, one message
      7. Resolve the parent; children close against it

**Watch out for.** Building the *unaffected* list matters as much as the
affected one. It is what turns "everything is broken" into a bounded
fault domain, and it is the step junior engineers consistently skip.

**Reference:** [ITIL 4 Incident
Management](https://www.axelos.com/certifications/itil-service-management)

### Q54. Monitoring shows 100% packet loss to a device users say is working fine

*Tier: L1. Safety: active test.*

**Short answer.** The monitoring server's path differs from the user
path, or ICMP is filtered somewhere on the monitoring path. Verify from
a second vantage point and with a non-ICMP check before declaring an
outage.

**What is actually going on.** Monitoring usually polls from a
management network with its own routing and its own firewall policy. A
change to a management ACL, a route withdrawal, or a newly enabled
control-plane policer breaks monitoring reachability while user traffic
on a different path is unaffected.

ICMP is also often deprioritised on device control planes, so a busy
router may drop your pings while forwarding transit traffic perfectly.

The general principle is worth stating plainly: a monitoring check
measures the path from the monitoring system. It does not measure the
health of the service.

**How to check**

                                                         [active test]
      1. Ping from a different source: another site, a jump host
      2. Test a non-ICMP service: SSH 22, SNMP 161, HTTPS 443
      3. Does SNMP polling still work while ICMP fails?
           That combination proves the device is up and ICMP is filtered.
      4. Check the management path for a recent routing or ACL change
      5. Confirm with a user-side transaction test

**Watch out for.** The strategic answer is to monitor the service rather
than the device. Synthetic transactions from the user's perspective,
meaning "can a client resolve, connect and authenticate," do not produce
this class of false positive at all.

**References:** [RFC 792,
ICMP](https://www.rfc-editor.org/rfc/rfc792.html) · [RFC 6192,
Protecting the Router Control
Plane](https://www.rfc-editor.org/rfc/rfc6192.html)

### Q55. How do you decide whether to escalate or keep troubleshooting?

*Tier: L1. Safety: read-only.*

**Short answer.** Escalate when the runbook is exhausted, when the fault
needs access or authority you do not have, or when continuing would
consume a meaningful share of the SLA. Escalate proactively rather than
at the breach point, and escalate with a complete handover rather than a
bare reassignment.

**What is actually going on.** Escalation is a judgement about time and
scope, not an admission of failure. Interviewers use this question to
find out whether a candidate hoards tickets out of pride.

Most NOCs use a time box tied to priority: a fixed number of minutes on
a P1 before escalation is mandatory, longer for lower priorities. Scope
is the second trigger. If the fault is in a system you cannot access,
more time does not help. Impact is the third: a P1 escalates faster than
a P3 for identical technical difficulty.

**How to work it**

    Escalate when any of these is true
      - runbook exhausted with no working hypothesis
      - the fix needs access or change authority you do not hold
      - elapsed time has used roughly half the SLA window
      - impact is expanding rather than contained
      - a vendor or carrier must be engaged

    Escalate WITH
      - symptom, exact start time, blast radius
      - what has been tested, and the result of each test
      - what has been RULED OUT, and the evidence for it
      - your current working hypothesis
      - any vendor case numbers already open

**Watch out for.** "What has been ruled out, and how" is the part junior
engineers omit and the part the receiving engineer needs most. Say it
explicitly; it is what separates a useful handover from a reassignment.

**Reference:** [ITIL 4 Incident
Management](https://www.axelos.com/certifications/itil-service-management)

### Q56. A maintenance window causes unexpected alerts to page on-call staff

*Tier: L1. Safety: change approval.*

**Short answer.** Schedule the suppression window before the change
begins, confirm every affected device *and its dependents* are tagged
into it, and verify the suppression is actually active at the start
rather than assuming.

**What is actually going on.** Suppression usually fails for one of
three reasons:

- The window covers the device being changed but not the devices
  downstream of it, so the dependents alert instead
- The window was scheduled in the wrong timezone, which is endemic in
  multi-region operations
- The change overran and the window expired mid-work, so alerts fired
  during the tail end when everyone had stopped watching

Each has a specific control: dependency-aware suppression,
timezone-explicit scheduling, and padding.

**How to work it**

    Before                                               [change approval]
      [ ] Suppression scheduled for the device AND its dependents
      [ ] Timezone stated explicitly, UTC preferred for multi-region
      [ ] Window padded 30 minutes either side of the planned work
      [ ] On-call told the window exists, in case anything leaks

    At the start
      [ ] Verify suppression is ACTIVE. Do not assume.
    After
      [ ] Confirm monitoring returns to normal and alerts resume
      [ ] Close the window explicitly if the work finishes early

**Watch out for.** Padding the *end* is the control that saves you most
often, because changes overrun far more than they finish early. An
unpadded 60-minute window that expires at minute 61 pages the whole team
during the riskiest part of the work.

**Reference:** [ITIL 4 Change
Enablement](https://www.axelos.com/certifications/itil-service-management)

### Q57. How do you document a resolved incident for future reference?

*Tier: L1. Safety: read-only.*

**Short answer.** Record the symptom in the user's own words, the
diagnostic path including what you ruled out, the root cause
distinguished from the trigger, the exact resolution, and a preventive
action with a named owner. Tag it so it is findable by symptom.

**What is actually going on.** Incident documentation fails at
retrieval, not at capture. The next engineer searches by symptom,
because the cause is precisely what they do not yet know. A record
titled by root cause is invisible to them.

Separating trigger from root cause matters too. "The link failed" is a
trigger. "The redundant path did not take over because the floating
static had the wrong administrative distance" is a root cause, and only
the second one prevents a repeat.

**Structure**

    Title            symptom-first, in user language
    Impact           who, how many, how long
    Timeline         detection, acknowledgement, mitigation, resolution
    Diagnosis        what was tested, what was ruled out, and how
    Trigger          the immediate event
    Root cause       the underlying condition that allowed it
    Resolution       exact commands and configuration applied
    Preventive       action, named owner, due date
    Tags             symptom keywords, device, vendor, service, site

**Watch out for.** Title it as the user's complaint, "branch office
users lost internet at 09:15," not as the engineering finding, "BGP
session flap on WAN2." Search hits on symptoms are what actually save
the next person time.

**References:** [ITIL 4 Problem
Management](https://www.axelos.com/certifications/itil-service-management)
· [Google SRE, Postmortem
Culture](https://sre.google/sre-book/postmortem-culture/)

### Q58. Bandwidth graphs show a steady climb toward saturation on a WAN link

*Tier: L2. Safety: read-only.*

**Short answer.** Treat it as capacity planning, not an incident.
Identify top talkers and applications with flow data, decide whether the
growth is legitimate business demand or something that should not be on
the link, then either upgrade with lead time or shape what does not
belong.

**What is actually going on.** Circuit upgrades take weeks to provision.
The same trend spotted at 70 percent utilisation is manageable; spotted
at 98 percent it is an outage already in progress.

Flow data decides which of two very different responses applies.
Legitimate growth means procurement plus a QoS policy protecting
interactive and voice traffic during peaks. Illegitimate growth, meaning
unscheduled backups, cloud sync, a runaway replication job, or
streaming, means shaping or scheduling and costs nothing.

**How to check**

    Flow analysis                                        [read-only]
      show flow monitor <name> cache aggregate ipv4 source address
      nfdump -R /flows -s srcip/bytes -n 20

    Answer these before recommending anything
      - Is the peak sustained or bursty?
      - What is the 95th percentile, not the maximum?
      - Is growth linear, or a step change? A step means a new service.
      - Does it correlate with a business change or a scheduled job?

**Watch out for.** Most carrier contracts bill on the 95th percentile,
so quote that rather than the peak when you build the business case.
Quoting the maximum overstates the problem and costs you credibility
with the people who approve the spend.

**References:** [RFC 7011,
IPFIX](https://www.rfc-editor.org/rfc/rfc7011.html) · [RFC 3176,
sFlow](https://www.rfc-editor.org/rfc/rfc3176.html)

### Q59. A P1 ticket sits untouched for 20 minutes because the engineer is on break

*Tier: L2. Safety: change approval.*

**Short answer.** Automatic escalation on unacknowledged alerts. If a P1
is not acknowledged within a short defined window, it escalates to the
secondary, then the team lead, without anyone having to notice.
Acknowledgement must be a separate tracked action from resolution.

**What is actually going on.** Assignment is not acknowledgement. A
ticket routed to a named person sits with that person whether or not
they are available, and nothing detects the silence.

The design detail that matters is separating acknowledgement, meaning a
human has seen this and is acting, from resolution, meaning the problem
is fixed. A system tracking only resolution cannot tell "nobody is
looking" apart from "someone is working on it."

**How to work it**

    Escalation ladder for P1
      T+0    page primary on-call
      T+5    unacknowledged -> page secondary
      T+10   unacknowledged -> page team lead
      T+15   unacknowledged -> page duty manager

    Supporting controls
      - acknowledgement is a distinct, tracked action
      - break coverage is explicit; no single point of on-call in a shift
      - a monitored group channel receives P1s, not one individual
      - measure time-to-acknowledge as a KPI alongside time-to-resolve

**Watch out for.** Treat this as a process design failure, not a
personal one. Answering "the engineer should have taken their phone" is
the wrong instinct and reads badly.

**Reference:** [Google SRE Book, Being
On-Call](https://sre.google/sre-book/being-on-call/)

### Q60. Multiple monitoring tools report the same outage at different severities

*Tier: L2. Safety: read-only.*

**Short answer.** Set priority from your organisation's impact and
urgency matrix, using validated blast radius and service criticality.
Tool severity is evidence feeding that decision, not the decision
itself.

**What is actually going on.** Different tools measure different things
and were configured by different people at different times. A network
platform may see an interface down as a warning while an application
monitor sees the dependent service as critical. Both are correct from
their own vantage point.

It is tempting to say "always take the highest severity," and that
instinct is understandable, but it is wrong as a *rule*. It lets a noisy
or misconfigured tool promote a P3 to a P1 and consume resources that a
genuine P1 needs. Tool severity reflects what that tool was configured
to think, which is not the same as business impact.

The practical middle ground: while you are still validating, err toward
treating it as the more serious case, because under-responding costs
service and over-responding costs effort. But set the *recorded
priority* from the matrix once you have established actual impact, and
do it quickly.

**How to work it**

    During the incident
      - determine real user and business impact first
      - apply the impact/urgency matrix to set priority
      - use tool severities as inputs, not as the verdict
      - while validating, act on the more cautious assumption
      - do not spend incident time arguing about tool disagreement

    After the incident
      - document which tool reported what, and why
      - agree one severity taxonomy across tools
      - designate an authoritative source per service
      - reduce overlap where duplication adds no signal

**Watch out for.** Persistent disagreement usually means one tool is
monitoring the wrong thing. That is worth chasing afterwards, because it
will eventually produce a false negative rather than just a false
positive, and false negatives are the ones that hurt.

**Reference:** [ITIL 4 Monitoring and Event
Management](https://www.axelos.com/certifications/itil-service-management)

### Q61. You've fixed an issue but the dashboard still shows red

*Tier: L2. Safety: active test.*

**Short answer.** Verify the service from a user's perspective before
you trust or dismiss the dashboard. If it is genuinely restored, force a
poll or clear the state. If the dashboard is right and your fix was too
narrow, keep working.

**What is actually going on.** Two possibilities that lead in opposite
directions.

The monitoring state may be stale. Polling intervals of five minutes are
common and some platforms hold a state until acknowledged.

Or the dashboard is right and you fixed one component while the
end-to-end service is still broken. That is the dangerous case, and an
engineer who assumes stale data and closes the ticket has just declared
a live outage resolved.

Testing the service the way a user experiences it resolves the ambiguity
in under a minute.

**How to work it**

      1. Test end to end as a user would, not just the component you changed
           resolve the name, connect, authenticate, complete a transaction
      2. If genuinely restored: force a poll, clear or acknowledge the state,
         confirm it goes green and stays green for a full interval
      3. If still failing: the dashboard is right. Keep troubleshooting.
      4. Watch one complete monitoring interval before closing

**Watch out for.** Never close on the assumption that monitoring is
lagging. Verifying the user experience takes a minute and is the
difference between a resolved incident and a reopened one with an angry
customer attached to it.

**Reference:** [Google SRE Workbook,
Monitoring](https://sre.google/workbook/monitoring/)

### Q62. Another team's change caused an outage and the NOC wasn't told

*Tier: L2. Safety: change approval.*

**Short answer.** Mandatory CAB notification to the NOC for any
network-impacting change, a change calendar visible to every team,
freeze windows for high-risk periods, and a standing rule that checking
the change calendar is the first step of every incident.

**What is actually going on.** This is an organisational boundary
failure, not a technical one. The NOC detects the impact and is
structurally the last to learn the cause, which inverts the correct
information flow.

The fix works in both directions. Changes must be visible to the NOC
before they happen, and the NOC must have change visibility built into
its incident workflow. Adding a required "recent changes checked" field
to the incident template is a small control with a disproportionate
effect, because it turns a good habit into a process step.

**How to work it**

    Preventive
      - CAB approval for any network-impacting change
      - NOC on the notification list for every approved change
      - shared change calendar readable by all teams, no exceptions
      - freeze windows for month-end, peak trading, major events

    Detective
      - incident template includes "changes in last 24h checked: Y/N"
      - automated configuration-diff alerting on network devices
      - change timestamps correlated automatically against alert timestamps

    Cultural
      - blameless post-incident reviews, so teams disclose changes readily

**Watch out for.** Automated configuration-diff alerting is the
strongest control here, because it catches undeclared changes regardless
of whether anyone followed the process. The changes that cause outages
are disproportionately the ones that skipped the process, and a calendar
will never show those.

**Reference:** [ITIL 4 Change
Enablement](https://www.axelos.com/certifications/itil-service-management)

### Q63. Your shift is ending but an incident isn't resolved

*Tier: L2. Safety: read-only.*

**Short answer.** Give a structured verbal handover backed by a written
record: current status, impact, everything tried and its result,
everything ruled out and the evidence, current hypothesis, planned next
steps, and any open vendor case numbers.

**What is actually going on.** Handover failures cause repeated work,
and repeated work on a live incident extends the outage.

The most commonly omitted item is negative evidence. Without it, the
incoming engineer re-tests the same hypotheses, sometimes for an hour,
before arriving where their colleague already was.

A verbal handover on its own is not enough. The incoming engineer will
need the detail again at 3 a.m. when the person who told them has gone
home.

**Structure**

    Written in the ticket, then walked through verbally
      Current status      what is broken now, and the blast radius
      Timeline            start, detection, key events
      Tried               each action and its result
      Ruled out           each hypothesis and the evidence that killed it
      Hypothesis          what you currently believe is happening
      Next steps          the specific action you would take next
      Dependencies        vendor case numbers, contacts, callback times
      Stakeholders        who has been told what, next update due when

    Confirm the incoming engineer can restate it before you leave.

**Watch out for.** The teach-back step, where the incoming engineer
summarises the situation in their own words, catches misunderstandings
that a one-way briefing hides completely. It costs two minutes and is
one of the most effective handover controls available.

**Reference:** [ITIL 4 Service Desk and Incident
Management](https://www.axelos.com/certifications/itil-service-management)

### Q64. Configuration drift is causing repeat incidents across similar devices

*Tier: L2. Safety: read-only.*

**Short answer.** You cannot fix drift by hand at scale. Establish a
source of truth for intended configuration, detect deviation
automatically, and remediate through templates rather than through
individual logins. Telemetry and config compliance tooling exist
precisely for this.

**What is actually going on.** Drift happens because devices are
configured individually over years by different people under different
pressures. Eventually no two "identical" branch routers are identical,
and an incident that was fixed on one recurs on the others.

Three capabilities close the gap, and they build on each other:

- **Source of truth.** A version-controlled intended configuration, per
  device role, from which actual configuration is derived rather than
  the other way round.
- **Continuous compliance checking.** Automated comparison of running
  config against intent, alerting on deviation. This is where a
  config-diff alert catches undeclared changes as a side benefit.
- **Streaming telemetry rather than polling.** SNMP polling every five
  minutes samples state. Model-driven telemetry pushes state changes as
  they happen, which turns "we noticed at the next poll" into "we knew
  immediately."

The interfaces worth knowing by name: NETCONF and RESTCONF for
configuration, YANG as the data model, gNMI for telemetry, and whichever
automation tool your organisation uses to apply templates.

**How to work it**

    Detect                                               [read-only]
      - scheduled config collection into version control
      - automated diff against the intended template
      - alert on deviation, with the diff attached

    Prevent                                              [change approval]
      - role-based templates as the only sanctioned change path
      - peer-reviewed changes to the template, not to the device
      - pre-deployment validation in a lab or a virtual instance

    Modernise
      - streaming telemetry (gNMI) alongside or instead of SNMP polling
      - NETCONF/RESTCONF with YANG models for structured change
      - dry-run and idempotent automation, so re-running is safe

**Watch out for.** The credible version of this answer is modest. Say
that you would start with read-only collection and diffing before
automating any change, because an automation tool applying a wrong
template to two hundred devices is a far larger outage than the drift it
was meant to fix.

**References:** [RFC 6241,
NETCONF](https://www.rfc-editor.org/rfc/rfc6241.html) · [RFC 8040,
RESTCONF](https://www.rfc-editor.org/rfc/rfc8040.html) · [RFC 7950, YANG
1.1](https://www.rfc-editor.org/rfc/rfc7950.html)

# Part IV. Cloud, Voice and the Physical Layer

Part IV spans the top and the bottom of the stack. Cloud platforms use
familiar words for unfamiliar behaviour, voice punishes inconsistency
rather than slowness, and the physical layer still causes a large share
of faults that are blamed on everything above it.

## Chapter 7. Cloud and Load Balancing

*Scenarios Q65 to Q72. Tier mix: 6 L2, 2 L3.*

### Orientation

Cloud networking uses familiar words for unfamiliar things, and that is
where most confusion comes from.

**A security group is not a firewall rule set in the traditional
sense.** It is stateful and attached to an instance. Allow traffic
outbound and the return is permitted automatically.

**A network ACL is stateless.** Allow outbound and you must *also* allow
the inbound return traffic on ephemeral ports, or the reply is silently
dropped. This single asymmetry causes more "it should work" cloud
tickets than anything else.

**A public IP address does not mean internet access.** The subnet also
needs a route to an internet gateway. Without it, the address exists and
does nothing.

**A load balancer only sends traffic to targets it believes are
healthy.** Almost every load balancer problem is really a health check
problem.

**Vendor note.** The examples in this chapter use AWS, because it is the
most common in NOC interviews and the CLI output is easy to reason
about. Azure and GCP have equivalent concepts under different names, and
the *principles* transfer. The *behaviour* sometimes does not, so verify
against your own provider's documentation rather than assuming.

### Scenarios in this chapter

  --------------------------------------------------------------------------------------------------------------------------------------------------------------
  ID                                                                                               Scenario                                           Tier
  ------------------------------------------------------------------------------------------------ -------------------------------------------------- ----------
  [Q65](#q65.-a-load-balancer-keeps-sending-traffic-to-a-backend-server-thats-down)                Health check depth                                 L2

  [Q66](#q66.-users-experience-session-drops-with-a-round-robin-load-balancer)                     Session persistence                                L2

  [Q67](#q67.-cloud-instances-cant-reach-the-internet-despite-having-a-public-ip)                  Routing and stateless ACLs                         L2

  [Q68](#q68.-a-hybrid-cloud-connection-shows-intermittent-bgp-flaps)                              BGP session instability                            L3

  [Q69](#q69.-an-app-in-the-cloud-is-reachable-internally-but-not-from-on-prem-over-vpn)           Hybrid routing                                     L2

  [Q70](#q70.-auto-scaling-added-instances-but-the-load-balancer-isnt-sending-them-traffic)        Target registration and health                     L2

  [Q71](#q71.-cross-region-cloud-traffic-has-unexpectedly-high-latency)                            Path and physics                                   L2

  [Q72](#q72.-a-security-group-update-blocked-traffic-that-used-to-work-through-the-nat-gateway)   Source address translation                         L3
  --------------------------------------------------------------------------------------------------------------------------------------------------------------

### Q65. A load balancer keeps sending traffic to a backend server that's down

*Tier: L2. Safety: read-only.*

**Short answer.** The health check is not testing what your users test.
It is probing the wrong port or path, checking too shallowly to notice
the failure, or polling too infrequently with too tolerant a threshold.

**What is actually going on.** A TCP health check confirms only that a
listener accepts connections. A hung application process will happily
keep accepting connections while returning errors to every request.

An HTTP check against `/` may hit a static page served by the web tier
while the application and database behind it are broken.

The interval and unhealthy threshold multiply into your detection
window. A 30-second interval with a threshold of three means 90 seconds
of traffic going into a dead server before anything happens.

Deep health checks that exercise the real dependency chain are the right
answer, but tune them carefully. A check that queries the database on
every probe can become a load problem in its own right.

**How to check**

                                                        # [read-only]
    aws elbv2 describe-target-health --target-group-arn <arn>
    aws elbv2 describe-target-group-attributes --target-group-arn <arn>
    F5                                                   [read-only]
      show ltm monitor http <name>
      show ltm pool <name> members

    Design questions
      - does the check path exercise the application, or just the web server?
      - interval x unhealthy threshold = detection window. Acceptable?
      - does the check follow redirects, or accept a 3xx as healthy by mistake?
      - is there a dedicated health endpoint that verifies real dependencies?

**Watch out for.** The right pattern is a dedicated health endpoint that
checks the service's actual dependencies and returns a non-200 when any
of them is unavailable. That pattern fixes the problem; tuning the timer
only shortens it.

**Reference:** [RFC 9110, HTTP
Semantics](https://www.rfc-editor.org/rfc/rfc9110.html)

### Q66. Users experience session drops with a round-robin load balancer

*Tier: L2. Safety: read-only.*

**Short answer.** No session persistence. Round robin sends consecutive
requests from the same user to different backends, and a backend holding
session state locally does not recognise a session created elsewhere.

**What is actually going on.** Round robin distributes evenly and knows
nothing about sessions. An application keeping session state in local
memory sees an authenticated user arrive as a stranger on every second
request.

Cookie-based persistence is the usual fix and works well behind NAT.
Source-IP persistence fails badly when many users share one NAT address,
because it concentrates an entire office onto a single backend.

Persistence also complicates maintenance, since draining a node means
waiting for sessions to expire. The architecturally better answer is to
externalise session state to a shared store so any backend can serve any
request.

**How to check**

                                                        # [read-only]
    aws elbv2 describe-target-group-attributes --target-group-arn <arn>
    #   stickiness.enabled, stickiness.type, stickiness.lb_cookie.duration_seconds
    F5                                                   [read-only]
      show ltm persistence persist-records
      show ltm pool <name> members       is one member carrying everything?

    Options, in order of architectural preference
      1. Externalise session state (Redis, Memcached, database)
      2. Cookie-based persistence            works behind NAT
      3. Source-IP persistence               breaks behind NAT

**Watch out for.** Saying that source-IP persistence is a poor choice
when clients sit behind a corporate NAT distinguishes someone who has
operated a load balancer from someone who has read about one.

**Reference:** [RFC 6265, HTTP State
Management](https://www.rfc-editor.org/rfc/rfc6265.html)

### Q67. Cloud instances can't reach the internet despite having a public IP

*Tier: L2. Safety: read-only.*

**Short answer.** A public IP is not connectivity. The subnet needs a
route to an internet gateway, the security group must permit the
traffic, and the network ACL must permit it in *both* directions because
NACLs are stateless.

**What is actually going on.** Cloud networking separates concerns that
on-premises networking bundles together.

An instance can hold a public address while sitting in a subnet whose
route table has no `0.0.0.0/0` entry pointing at an internet gateway.
That is precisely what makes a subnet private.

The stateful versus stateless distinction is the one interviewers probe.
Security groups are stateful, so an outbound allow implies the return is
permitted. Network ACLs are stateless, so an outbound allow without a
matching inbound rule for the ephemeral port range silently drops every
response.

**How to check**

                                                        # [read-only]
    aws ec2 describe-route-tables \
      --filters Name=association.subnet-id,Values=<subnet>
    aws ec2 describe-internet-gateways \
      --filters Name=attachment.vpc-id,Values=<vpc>
    aws ec2 describe-security-groups --group-ids <sg>
    aws ec2 describe-network-acls \
      --filters Name=association.subnet-id,Values=<subnet>

    # Let the platform answer it definitively
    aws ec2 create-network-insights-path ...
    aws ec2 start-network-insights-analysis ...
    Checklist
      [ ] Route table has 0.0.0.0/0 pointing at an internet gateway
      [ ] Internet gateway attached to the VPC
      [ ] Security group permits the outbound traffic
      [ ] NACL permits outbound AND inbound ephemeral ports (1024-65535)
      [ ] The instance actually has a public or Elastic IP associated

**Watch out for.** Reachability Analyzer answers this deterministically
and names the exact blocking component. It is faster and more reliable
than checking five configurations by hand.

**References:** [RFC 1918, Private Address
Space](https://www.rfc-editor.org/rfc/rfc1918.html) · [AWS VPC
Documentation](https://docs.aws.amazon.com/vpc/)

### Q68. A hybrid cloud connection shows intermittent BGP flaps

*Tier: L3. Safety: read-only.*

**Short answer.** Read the actual reset reason before theorising. The
log and the notification code tell you which class of failure you have,
and the classes need different responses.

**What is actually going on.** Two popular explanations are wrong.

BGP peers **negotiate** the hold time and use the smaller of the two
values, so a configured "mismatch" is not by itself a cause of
intermittent flapping. And an MD5 authentication mismatch normally
prevents the session from establishing at all rather than producing
periodic drops.

What actually causes recurring flaps:

  -----------------------------------------------------------------------
  Cause                            Evidence
  -------------------------------- --------------------------------------
  Sustained loss or congestion on  Interface errors, optical levels,
  the circuit                      provider status

  Control-plane policing or CPU    High CPU, CoPP drops, keepalives
  starvation                       generated late

  Physical layer degradation       Rising CRC, Rx power drifting toward
                                   the threshold

  LAG member failure under a       One member down or erroring, bundle
  bundled circuit                  still "up"

  BFD timers too aggressive for    BFD down while BGP alone would have
  the path                         stayed up

  Provider maintenance or churn    Their status page, their case notes

  Max-prefix limit exceeded        A specific notification, session torn
                                   down deliberately
  -----------------------------------------------------------------------

**How to check**

                                                         [read-only]
    show bgp neighbor <ip> | include state|Last reset|hold time|keepalive
    show logging | include BGP-5-ADJCHANGE|BGP-3-NOTIFICATION
    show interface <if> | include errors|CRC|input rate
    show interface transceiver detail        Rx dBm within spec?
    show bfd neighbors detail
    show processes cpu sorted                is the control plane starved?
    show policy-map control-plane            CoPP drops?

**Watch out for.** Open the provider ticket with the circuit ID, exact
flap timestamps, and your optical readings attached. Carriers
deprioritise vague reports, and a ticket carrying light levels and
timestamps moves through their process substantially faster than one
that says "our BGP keeps flapping."

**References:** [RFC 4271,
BGP-4](https://www.rfc-editor.org/rfc/rfc4271.html) · [RFC 5880,
BFD](https://www.rfc-editor.org/rfc/rfc5880.html)

### Q69. An app in the cloud is reachable internally but not from on-prem over VPN

*Tier: L2. Safety: read-only.*

**Short answer.** Either route propagation is not delivering the
prefixes, the subnet is associated with the wrong route table, the
security group does not permit the on-premises source range, or the two
address spaces overlap.

**What is actually going on.** Working internally tells you the
application is running and that the rules covering *internal* sources
are correct. It does not tell you the security group permits your
on-premises CIDR, and those are different rules.

Cloud route tables do not automatically learn from a VPN gateway.
Propagation must be enabled explicitly per route table, and a subnet
associated with the wrong route table has no path back on-premises even
though the tunnel itself is fine.

Overlapping CIDR ranges produce a particularly confusing symptom,
because each side resolves the destination locally and traffic never
enters the tunnel at all.

**How to check**

                                                        # [read-only]
    aws ec2 describe-route-tables --route-table-ids <rtb>
    aws ec2 describe-vpn-connections --vpn-connection-ids <vpn>
    aws ec2 describe-security-groups --group-ids <sg>
    On-premises                                          [read-only]
      show ip route <cloud-cidr>
      show crypto ipsec sa | include encaps|decaps

    Checklist
      [ ] Route propagation enabled on the correct route table
      [ ] The subnet is ASSOCIATED with that route table
      [ ] Security group permits the on-premises source CIDR specifically
      [ ] NACL permits it in both directions
      [ ] No CIDR overlap between on-prem and the VPC
      [ ] Return path exists: check both encaps and decaps counters

**Watch out for.** Check the subnet-to-route-table *association*, not
just the route table contents. A correct route table that the subnet is
not associated with is a very common cause of this symptom.

**References:** [RFC 1918](https://www.rfc-editor.org/rfc/rfc1918.html)
· [AWS VPC Route Tables](https://docs.aws.amazon.com/vpc/)

### Q70. Auto-scaling added instances but the load balancer isn't sending them traffic

*Tier: L2. Safety: read-only.*

**Short answer.** Read the target health state and its reason code. The
state narrows it down, but each state has several possible reasons and
the reason code is what actually names the fault.

**What is actually going on.** Target health states are commonly
over-simplified. In reality:

  ----------------------------------------------------------------------------
  State         What it can mean
  ------------- --------------------------------------------------------------
  `unused`      The target group is not used by a listener, or the
                Availability Zone is not enabled for the load balancer, or the
                target is in an invalid state, or its IP is unusable. Not
                simply "not registered."

  `initial`     Registration is still in progress, or initial health checks
                have not completed yet.

  `unhealthy`   Registered, checked, and failing. Read the reason code for
                which check failed.

  `draining`    Deregistration in progress, finishing existing connections.
  ----------------------------------------------------------------------------

The relationship between Auto Scaling and load balancer health is also
worth stating correctly. The **Auto Scaling health check grace period**
prevents Auto Scaling from replacing an instance prematurely while it
boots. It does not pause load balancer health checks, which run in
parallel and independently decide whether the target receives traffic.

So a grace period that is too short causes premature *replacement*,
producing a loop of instances that boot, get killed and get replaced. A
health check that is too aggressive for the application's startup causes
the target to sit `unhealthy` and never take traffic. Related, but
different failures.

**How to check**

                                                        # [read-only]
    aws elbv2 describe-target-health --target-group-arn <arn>
    #   read both State and Reason for each target

    aws autoscaling describe-auto-scaling-groups --auto-scaling-group-names <asg>
    #   confirm TargetGroupARNs is populated

    aws autoscaling describe-auto-scaling-activities --auto-scaling-group-name <asg>
    #   are instances being terminated and replaced in a loop?
    Also check
      - health check grace period vs actual application startup time
      - health check interval and threshold vs startup time
      - security group on instances permits the load balancer's check port
      - the new Availability Zone's subnet is enabled on the load balancer

**Watch out for.** A grace period shorter than application startup
causes an endless scale-up-and-terminate loop that also runs up cost
quietly. It is a common real-world failure and a good detail to raise
unprompted.

**Reference:** [AWS Target Group Health
Checks](https://docs.aws.amazon.com/elasticloadbalancing/latest/application/target-group-health-checks.html)

### Q71. Cross-region cloud traffic has unexpectedly high latency

*Tier: L2. Safety: active test.*

**Short answer.** Establish the physical floor for that distance first,
then determine whether the measured latency is close to it. If it is,
this is geography and not a fault. If it is well above it, look at the
path and at whether traffic is leaving the provider's network.

**What is actually going on.** Start with physics, because it bounds
everything else.

Light in fibre travels at roughly **200 km per millisecond**. So:

    one-way distance / 200  =  one-way propagation in ms
    round-trip distance / 200  =  round-trip propagation in ms

A round trip covering 15,000 km cannot be faster than about **75 ms** of
pure propagation. Real fibre routes are longer than the straight-line
distance, and equipment and queuing add more, so 90 to 110 ms would be
entirely normal for that path. What tells you something is wrong is
measured latency several times the floor, or high jitter.

On path behaviour, assert only what you can verify. AWS states that
traffic between EC2 instances in different Regions stays on the AWS
global network, including when public IP addresses are used. Do not
claim that cross-region traffic "defaults to the public internet,"
because for that provider it is not true. Other providers and other
service types behave differently, so verify rather than generalise.

What genuinely causes worse-than-expected cross-region latency: an
indirect route, a hop through an on-premises or third-party transit
point in a hybrid design, congestion, or an application making many
sequential round trips so latency multiplies.

**How to check**

                                                        # [active test]
    mtr -rwzc 100 <remote-region-endpoint>   # does the path leave the provider?
    ping -c 100 <remote-endpoint>            # jitter as well as latency
    Assess in this order
      1. Theoretical floor for the distance (round trip km / 200)
      2. Measured latency: near the floor, or several times it?
      3. Jitter: high jitter means congestion; steady high means distance
      4. Path: any hops outside the provider's network?
      5. Application behaviour: how many sequential round trips per transaction?

    Options if it is genuinely path-related
      VPC or Transit Gateway peering, provider backbone services,
      global accelerator products, or moving the workload closer to the user

**Watch out for.** Establishing the physical lower bound before
escalating prevents an embarrassing carrier ticket. It also stops you
raising a P2 against the laws of physics, which does happen.

**References:** [RFC 6349, TCP Throughput
Testing](https://www.rfc-editor.org/rfc/rfc6349.html) · [AWS EC2
Instance IP
Addressing](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/using-instance-addressing.html)

### Q72. A security group update blocked traffic that used to work through the NAT gateway

*Tier: L3. Safety: read-only.*

**Short answer.** Traffic leaving through a NAT gateway arrives at the
destination carrying the gateway's public address, not the instance's
private one. If the destination's allow list references private
addresses or security group IDs, it no longer matches. Confirm it from
flow log *records*, not from the flow log configuration.

**What is actually going on.** Security groups can reference other
security groups as sources, which is the correct pattern for traffic
staying inside the VPC.

The moment traffic exits through a NAT gateway, the source becomes the
gateway's public IP. A security-group reference cannot match that. This
bites hardest when a service is reached over the internet rather than
through a private endpoint.

The architecturally better fix is often a private endpoint, which keeps
traffic on the provider's network. Do not overstate source preservation,
though. Whether the client's original address is preserved depends on
the endpoint type, the target type, the protocol, and whether client IP
preservation is enabled. It is not a universal guarantee.

**How to check**

                                                        # [read-only]
    aws ec2 describe-nat-gateways --nat-gateway-ids <nat>
    #   note the associated Elastic IP

    aws ec2 describe-security-groups --group-ids <sg>

    # Flow logs: describe-flow-logs lists CONFIGURATIONS, not records.
    # To read the actual REJECT entries, query the destination:
    aws logs start-query \
      --log-group-name <flow-log-group> \
      --start-time <epoch> --end-time <epoch> \
      --query-string 'fields srcAddr, dstAddr, dstPort, action
                      | filter action = "REJECT"
                      | sort @timestamp desc | limit 50'

    # Or, if flow logs go to S3, query them with Athena.
    Reading the result
      If srcAddr shows the NAT gateway's Elastic IP, the destination's
      allow list is the problem.

    Fixes, in order of preference
      1. Private endpoint, so traffic never leaves the private network
      2. Allow-list the NAT gateway's Elastic IP at the destination
      3. Document the NAT Elastic IP as a managed dependency, so the next
         change does not forget it

**Watch out for.** The command that lists flow log configurations and
the query that returns flow log records are different things, and
confusing them wastes real time during an incident. Know which one gives
you evidence.

**References:** [RFC 3022, Traditional IP
NAT](https://www.rfc-editor.org/rfc/rfc3022.html) · [AWS VPC
Documentation](https://docs.aws.amazon.com/vpc/)

## Chapter 8. VoIP and QoS

*Scenarios Q73 to Q78. Tier mix: 6 L2.*

### Orientation

Voice traffic is unusual because it cares about *consistency* far more
than *speed*. A call needs small packets delivered on time, every time.
A file transfer just needs the bytes to arrive eventually.

Three numbers define acceptable voice quality, and knowing them turns a
vague complaint into a measurable fact:

  -----------------------------------------------------------------------
  Metric            Target            What happens beyond it
  ----------------- ----------------- -----------------------------------
  One-way latency   under 150 ms      People start talking over each
                                      other

  Jitter            under 30 ms       Choppy, robotic audio

  Packet loss       under 1 percent   Dropouts and clipped words
  -----------------------------------------------------------------------

Two protocols do the work. **SIP** sets up, modifies and tears down the
call. **RTP** carries the actual audio. They travel separately, often
through different ports and sometimes different paths, which is why a
call can connect perfectly and then have no sound.

**QoS** is how you protect voice from everything else. It works by
marking packets, usually DSCP EF for voice, and then treating marked
packets preferentially at every congestion point. The catch is that it
only works if the marking survives every hop. One device that does not
trust DSCP and rewrites it to zero disables the entire scheme
downstream.

### Scenarios in this chapter

  -------------------------------------------------------------------------------------------------------------------------------------------------
  ID                                                                                  Scenario                                          Tier
  ----------------------------------------------------------------------------------- ------------------------------------------------- -----------
  [Q73](#q73.-calls-are-fine-most-of-the-day-but-become-choppy-around-5-pm)           Time-correlated congestion                        L2

  [Q74](#q74.-one-way-audio-is-reported-on-calls-between-two-sites)                   RTP direction and NAT                             L2

  [Q75](#q75.-voip-quality-complaints-only-come-from-wireless-users-not-wired-ones)   Voice over WLAN                                   L2

  [Q76](#q76.-softphone-calls-drop-at-a-precise-repeating-interval)                   Session timers                                    L2

  [Q77](#q77.-after-a-wan-bandwidth-upgrade-voice-quality-got-worse)                  QoS after a change                                L2

  [Q78](#q78.-conference-calls-degrade-only-above-about-10-participants)              Media server capacity                             L2
  -------------------------------------------------------------------------------------------------------------------------------------------------

### Q73. Calls are fine most of the day but become choppy around 5 PM

*Tier: L2. Safety: read-only.*

**Short answer.** Bandwidth contention at end of day from backups,
updates and cloud sync. Confirm the correlation on the interface graphs,
verify voice is marked correctly and that the marking survives every
hop, and check the priority queue is doing its job on the WAN edge.

**What is actually going on.** Time-correlated degradation is congestion
until proven otherwise.

QoS protects voice only if three things all hold: packets are marked at
the source, every device on the path preserves that marking, and the
egress interface has a priority queue with enough bandwidth reserved. A
break at any single hop, typically a switch that does not trust DSCP and
zeroes it, silently disables the whole scheme from that point onward.

**How to check**

                                                         [read-only]
    show policy-map interface <wan-if>
      -> priority queue drops? total drops rising at the same time daily?
    show interface <wan-if> | include rate|drops
    show mls qos interface <if>            is the trust boundary correct?

    Per-hop marking check                                [active test]
      Capture at each hop and confirm DSCP 46 (EF) survives:
      client -> switch -> WAN router -> provider handoff

**Watch out for.** Quote the three voice targets by number. Numbers
define what "good" means, and they let you prove or disprove the
complaint from monitoring data rather than from user perception.

**References:** [RFC 3550,
RTP](https://www.rfc-editor.org/rfc/rfc3550.html) · [RFC 4594, DiffServ
Service Classes](https://www.rfc-editor.org/rfc/rfc4594.html) · [ITU-T
G.114](https://www.itu.int/rec/T-REC-G.114)

### Q74. One-way audio is reported on calls between two sites

*Tier: L2. Safety: read-only.*

**Short answer.** RTP is flowing in one direction only. Read the SDP in
the signalling to find out where each endpoint expects to receive media,
then capture at both ends to see which stream is missing.

**What is actually going on.** SIP signalling and RTP media travel
separately. The SDP body inside the SIP messages advertises the address
and port where each endpoint expects to receive audio.

When an endpoint sits behind NAT, that advertised address is a private
one the far side cannot reach, so media flows one way and not the other.
SIP ALG exists to rewrite those SDP addresses, but implementations are
inconsistent and often rewrite them wrongly. That is why disabling ALG
sometimes fixes this and sometimes causes it, and why blanket advice
about ALGs is unhelpful.

**How to check**

                                                         [read-only / active test]
      1. Capture SIP signalling; read the SDP c= and m= lines from both ends
      2. Is each advertised address routable from the other side?
      3. Capture RTP at both ends:
           tcpdump -i <if> -n udp portrange 16384-32768
         Which direction is missing?
      4. Check SIP ALG state on every firewall in the path
      5. Confirm the RTP port range is permitted in both directions

    Cisco                                                [service-affecting]
      debug ccsip messages
      show voip rtp connections

**Watch out for.** Get the direction right. Media flows *from* the side
that is not being heard. If site A cannot hear site B, the missing
stream is B to A, so investigate B's outbound path and A's inbound
policy. Many candidates fumble this and immediately look in the wrong
place.

**References:** [RFC 3261,
SIP](https://www.rfc-editor.org/rfc/rfc3261.html) · [RFC 4566,
SDP](https://www.rfc-editor.org/rfc/rfc4566.html) · [RFC 3550,
RTP](https://www.rfc-editor.org/rfc/rfc3550.html)

### Q75. VoIP quality complaints only come from wireless users, not wired ones

*Tier: L2. Safety: read-only.*

**Short answer.** The wireless segment is the only difference, so look
there: WMM prioritisation, airtime contention, retransmissions, and
roaming delay. Verify WMM is enabled and that DSCP survives the
wired-to-wireless translation.

**What is actually going on.** Wired switches give every port full
duplex and dedicated bandwidth. Wireless is a shared, half-duplex medium
where every station contends for airtime.

Without WMM mapping voice into the AC_VO access category, a voice frame
waits behind bulk transfers. Retransmissions add jitter directly,
because a retried frame arrives late rather than not at all, and jitter
is what destroys call quality.

Roaming adds a second failure mode. A full reauthentication between
access points takes long enough to be audible on a call while being
completely invisible on a data session. That is what 802.11r fast
transition solves.

This scenario covers **enterprise voice on your own call platform**.
Carrier Wi-Fi calling built into a mobile handset is a different
problem, because the media is encrypted to the operator's gateway and
your WLAN cannot see or mark it. See
[Q49](#q49.-wi-fi-calling-quality-is-choppy-while-data-works-fine).

**How to check**

                                                         [read-only]
    show wlan <id> | include WMM|QoS|Fast Transition
    show client detail <mac>
      -> retry percentage, data rate, RSSI, SNR, access category
    show ap auto-rf <ap-name>              channel utilisation

    Thresholds for voice over wireless
      RSSI                 better than -67 dBm
      SNR                  25 dB or better
      Retries              under 10 percent
      Channel utilisation  under 40 percent
      Roam time            under 50 ms, which needs 802.11r

**Watch out for.** Voice needs a stricter RF design than data: more cell
overlap, lower transmit power, and coverage validated at -67 dBm rather
than -70 dBm. A network that is perfectly adequate for laptops can be
genuinely unfit for handsets, and saying so shows design awareness
rather than just troubleshooting skill.

**References:** [IEEE 802.11e /
WMM](https://standards.ieee.org/ieee/802.11/7028/) · [RFC 8325, Mapping
DiffServ to 802.11](https://www.rfc-editor.org/rfc/rfc8325.html)

### Q76. Softphone calls drop at a precise repeating interval

*Tier: L2. Safety: read-only.*

**Short answer.** Precision means a timer. Capture the signalling, find
which side sends BYE and why, then compare the interval against the
configured session timer, registration refresh, and NAT idle timeout
until one of them matches.

**What is actually going on.** SIP session timers require a periodic
re-INVITE or UPDATE to confirm the session is alive. If the refresh does
not arrive, or its response is lost, both ends tear the call down at
expiry.

The other candidate is NAT binding expiry. The firewall drops the UDP
mapping after an idle period, the refresh cannot traverse it, and the
call ends.

Both produce a precisely repeating interval, which is why the method is
to compare configured timer values against the measured one until you
find the match rather than guessing.

**How to check**

    Capture the SIP dialogue                             [read-only]
      Session-Expires header value and refresher (uac or uas)
      Is the re-INVITE or UPDATE sent, and answered?
      Who sends the BYE? That side is enforcing the timer.

    Compare the measured interval against
      SIP Session-Expires
      SIP registration refresh interval
      Firewall UDP idle timeout
      NAT keepalive interval on the client

    Cisco                                                [read-only]
      show sip-ua timers

**Watch out for.** Identifying which side sends the BYE tells you whose
configuration to change. Without it you are adjusting timers on both
ends and hoping, which is not troubleshooting.

**References:** [RFC 4028, Session Timers in
SIP](https://www.rfc-editor.org/rfc/rfc4028.html) · [RFC
3261](https://www.rfc-editor.org/rfc/rfc3261.html) · [RFC
4787](https://www.rfc-editor.org/rfc/rfc4787.html)

### Q77. After a WAN bandwidth upgrade, voice quality got worse

*Tier: L2. Safety: read-only.*

**Short answer.** Something about the change broke the QoS treatment.
Look for the policy being detached, misapplied to a new interface, or
referencing a stale bandwidth, and check whether the provider handoff
now treats your markings differently.

**What is actually going on.** The popular version of this answer does
not hold up. A shaper left at the old rate would preserve the *previous*
bottleneck, which is not obviously worse than before. To explain quality
getting genuinely *worse*, you need something that changed for the
worse:

- **The service policy is no longer attached.** A new or replaced WAN
  interface does not inherit the old configuration, so voice is now
  best-effort where it was previously prioritised.
- **The trust boundary was reset.** A replaced interface or line card
  can default to untrusted, zeroing DSCP on ingress.
- **The provider handoff changed.** A new circuit often means a new
  handoff with a different marking agreement. Your EF may now be
  remarked or ignored in their network.
- **The parent shape rate is wrong in the other direction.** Shaping to
  more than the circuit can actually deliver moves the queue into the
  provider's network, where your QoS policy has no effect at all.
- **Queue or serialisation parameters changed** with the new interface
  type or speed.

A stale shaper set to the old, lower rate is still worth finding and
fixing, but as a capacity problem rather than as the explanation for
worse audio.

**How to check**

                                                         [read-only]
    show policy-map interface <wan-if>     is a policy attached at all?
    show run interface <wan-if> | include bandwidth|service-policy
    show interface <wan-if> | include BW|rate
    show mls qos interface <wan-if>        trust state after the change
    show policy-map interface | include drops
    Fix                                                  [change approval]
      interface <wan-if>
        bandwidth <new-kbps>            reference for percentage-based classes
        service-policy output PARENT-SHAPER
      policy-map PARENT-SHAPER
        class class-default
          shape average <rate at or just below the contracted rate>
          service-policy CHILD-QOS

**Watch out for.** Add "verify and retune QoS, and confirm the service
policy is still attached" as a standard line item in every circuit
change record. A checklist item prevents the problem; a troubleshooting
victory only fixes it once.

**References:** [RFC 2474, DiffServ
Field](https://www.rfc-editor.org/rfc/rfc2474.html) · [RFC
4594](https://www.rfc-editor.org/rfc/rfc4594.html)

### Q78. Conference calls degrade only above about 10 participants

*Tier: L2. Safety: read-only.*

**Short answer.** A resource ceiling on the media server or bridge: CPU,
memory, transcoding capacity, or the aggregate bandwidth of the mixed
streams. A consistent participant threshold points at capacity, not at
the network.

**What is actually going on.** A mixing bridge decodes every incoming
stream, mixes, and re-encodes for each participant. Cost scales sharply
with participant count and even more sharply when participants use
different codecs and require transcoding.

Bandwidth scales too. Twenty participants at 100 kbps each is 2 Mbps
inbound, plus the mixed output streams.

A consistent threshold is the signature of a resource limit. Identify
which resource by watching CPU, memory, transcoding session count and
interface utilisation as participants join.

**How to check**

    While a call ramps up, watch                         [read-only]
      media server CPU and memory
      active transcoding sessions vs licensed or hardware capacity
      interface utilisation on the media server uplink
      loss and jitter on the RTP streams

    Cisco                                                [read-only]
      show call active voice brief
      show voice dsp group all           DSP resource exhaustion
    How to read it
      Consistent threshold       -> capacity limit
      Random degradation         -> network path problem
      Only certain participants  -> codec mismatch forcing transcoding

**Watch out for.** Check whether degradation hits everyone or only some
participants. Selective degradation usually means a codec mismatch
driving transcoding for a subset, and that is fixed by standardising the
codec rather than by buying hardware.

**References:** [RFC 3550,
RTP](https://www.rfc-editor.org/rfc/rfc3550.html) · [RFC 7667, RTP
Topologies](https://www.rfc-editor.org/rfc/rfc7667.html)

## Chapter 9. Physical Layer and Cabling

*Scenarios Q79 to Q84. Tier mix: 4 L1, 2 L2.*

### Orientation

Layer 1 is where a surprising share of "network" problems actually live,
and it is the layer most often skipped because it involves walking
somewhere with a torch.

A few things worth knowing before you start:

**A link light means almost nothing.** It confirms two devices detected
each other electrically. It does not confirm the cable meets its
specification, that all four pairs work, or that data is arriving
intact.

**Copper has a distance limit of 100 metres**, and that includes the
patch cords at both ends, not just the run inside the wall.

**Fibre is about light budget.** Every connector, splice and kilometre
of glass costs you a fraction of a decibel. Exceed the budget and the
link fails or errors, and the most common cause by a wide margin is a
dirty connector.

**Counters tell the story.** CRC errors mean corruption. Late collisions
mean duplex mismatch. Learn to read them and you will diagnose most
Layer 1 faults from the CLI before touching anything.

### Scenarios in this chapter

  --------------------------------------------------------------------------------------------------------------------------------------------------
  ID                                                                                    Scenario                                        Tier
  ------------------------------------------------------------------------------------- ----------------------------------------------- ------------
  [Q79](#q79.-a-newly-terminated-cable-passes-a-link-light-but-has-a-high-error-rate)   Termination quality                             L1

  [Q80](#q80.-a-fibre-link-shows-light-loss-readings-well-beyond-spec)                  Optical loss                                    L1

  [Q81](#q81.-a-patch-panel-port-works-but-the-same-run-at-the-wall-jack-doesnt)        Segment isolation                               L1

  [Q82](#q82.-a-copper-run-works-at-100-mbps-but-fails-at-gigabit)                      Pair count and category                         L1

  [Q83](#q83.-an-sfp-transceiver-shows-link-down-despite-being-properly-seated)         Optic compatibility                             L2

  [Q84](#q84.-multiple-ports-on-the-same-switch-card-show-errors-after-a-power-event)   Hardware damage                                 L2
  --------------------------------------------------------------------------------------------------------------------------------------------------

### Q79. A newly terminated cable passes a link light but has a high error rate

*Tier: L1. Safety: read-only.*

**Short answer.** Poor termination. Either the pairs do not follow the
T568A or T568B assignment, or they were untwisted too far at the
connector, causing crosstalk. Re-terminate and test with a certifier,
not a continuity tester.

**What is actually going on.** A link light requires far less than a
compliant cable. Fast Ethernet uses two pairs, so a badly wired cable
can link at 100 Mbps while failing entirely at gigabit.

The specific fault is usually a **split pair**, where the wires sit in
the correct pin positions but are paired incorrectly. Continuity testers
pass this happily while crosstalk is severe. Untwisting more than about
13 mm at the termination destroys the noise cancellation the twist
provides.

Only a certifier measuring NEXT, return loss and insertion loss will
find either problem.

**How to check**

    Switch side                                          [read-only]
      show interface <if> counters errors    CRC, alignment, symbol errors
      show interface <if> status             did it negotiate gigabit or not?

    Cable side
      Certifier test (Fluke DSX or equivalent), not a continuity tester
      Check wiremap, NEXT, PS-NEXT, return loss, insertion loss, length

    Common findings
      split pair             passes continuity, fails NEXT
      untwist beyond 13 mm   fails NEXT at the connector
      mixed T568A / T568B    crossover where a straight cable was intended
      run beyond 100 m       fails insertion loss

**Watch out for.** A cable negotiating 100 Mbps rather than 1 Gbps
strongly suggests a two-pair fault. That single observation from
`show interface status` narrows the diagnosis before anyone walks to the
patch panel.

**References:** [ANSI/TIA Standards](https://tiaonline.org/) · [IEEE
802.3ab, 1000BASE-T](https://standards.ieee.org/ieee/802.3/10422/)

### Q80. A fibre link shows light-loss readings well beyond spec

*Tier: L1. Safety: read-only.*

**Short answer.** Contamination, damage, or too much loss along the
path. Clean the connectors first, because that resolves the majority of
cases, then measure and locate faults with an OTDR if it is still out of
spec.

**What is actually going on.** Contamination is the leading cause of
optical failure in the field. A single dust particle on a core narrower
than a human hair scatters enough light to break the budget, and
inspecting a connector without a scope tells you nothing at all.

Beyond contamination, the budget adds up:

  -----------------------------------------------------------------------
  Element                                  Typical loss
  ---------------------------------------- ------------------------------
  Mated connector pair                     0.3 to 0.75 dB

  Fusion splice                            around 0.1 dB

  Multi-mode fibre at 850 nm               around 3.0 dB per km

  Single-mode fibre at 1310 nm             around 0.4 dB per km
  -----------------------------------------------------------------------

Mixing fibre types, whether single-mode with multi-mode or 50 micron
with 62.5 micron, produces large mismatch losses that no amount of
cleaning fixes.

**How to check**

                                                         [read-only]
    show interface transceiver detail
      -> Tx power, Rx power, and the low and high warning thresholds

    Field procedure
      1. Inspect with a fibre scope BEFORE cleaning, and after
      2. Clean with a proper cleaner. Not compressed air. Not a sleeve.
      3. Re-measure Rx power
      4. Still out of spec? OTDR to locate the event by distance

**Watch out for.** Inspect before cleaning as well as after.
Photographing the contamination gives you evidence for the incident
record and, in a contracted environment, for the conversation with
whoever installed it.

**References:** [ISO/IEC 11801](https://www.iso.org/standard/66182.html)
· [IEC 61300-3-35, Connector
Cleanliness](https://webstore.iec.ch/publication/24071)

### Q81. A patch panel port works but the same run at the wall jack doesn't

*Tier: L1. Safety: read-only.*

**Short answer.** The fault is between the patch panel and the wall
jack, so test each segment individually to find which one fails.

**What is actually going on.** A structured cabling channel is several
segments in series, and a working test at the panel only validates the
equipment side.

The horizontal run inside the wall is the segment most likely to have
been damaged, by drilling, rodents, tight bends, or being pulled during
someone else's work, and it is the segment nobody can see. The jack
termination is the next candidate, particularly if it was terminated at
a different time or by a different installer than the panel.

**How to check**

    Test each segment separately
      1. Patch panel port to switch          known good?
      2. Panel to jack, permanent link test  certifier at both ends
      3. Jack to device, with a known-good patch cord

    Certifier readings that name the fault
      Length shorter than expected      break in the run at that distance
      Wiremap fault at one end only     that termination
      High NEXT on the permanent link   run damage or bad termination
      Open on specific pins             partial break or bad punch-down

**Watch out for.** Record the certifier's reported distance to the
fault. It turns a wall-opening exercise into a targeted repair at a
known point, which is the difference between a two-hour job and a
two-day one.

**Reference:** [ANSI/TIA Standards](https://tiaonline.org/)

### Q82. A copper run works at 100 Mbps but fails at gigabit

*Tier: L1. Safety: read-only.*

**Short answer.** Gigabit uses all four pairs; Fast Ethernet uses two. A
fault on the pairs that only gigabit needs, a run over 100 metres, or
degraded crosstalk performance will produce exactly this. Certify the
run and check the total channel length.

**What is actually going on.** 100BASE-TX transmits on two pairs and
ignores the other two entirely, so any fault on those pairs is invisible
until you try to run gigabit. 1000BASE-T uses all four pairs
bidirectionally with echo cancellation, which is far less tolerant of
crosstalk and return loss.

A word of care on cable category, because this is commonly stated
wrongly. IEEE 802.3ab specified 1000BASE-T to operate over four-pair
**Category 5** balanced copper cabling. Cat5e is the safer certification
baseline and is what you should install today, because it adds specified
limits for return loss and far-end crosstalk that make gigabit reliable
in practice. But saying "Cat5 was never specified for gigabit" is not
accurate, and an interviewer who knows the standard will notice.

The practical point stands: an old Cat5 run that was marginal at 100
Mbps often fails certification for gigabit, and the fix is to
re-terminate or replace it.

**How to check**

                                                         [read-only]
    show interface <if> status              what did it negotiate?
    show interface <if> capabilities
    show interface <if> counters errors

    Certify and confirm
      [ ] All four pairs continuous and correctly mapped
      [ ] Cable category printed on the jacket
      [ ] Total channel length under 100 m INCLUDING patch cords
      [ ] NEXT and return loss within the relevant category limits
      [ ] No mid-span joints or unrated couplers in the run

**Watch out for.** Cheap unrated couplers used to extend a run are a
frequent hidden cause. They pass continuity, degrade crosstalk badly,
and are usually tucked above a ceiling tile where nobody thinks to look.

**References:** [IEEE 802.3ab interpretation, 1000BASE-T over Category
5](https://standards.ieee.org/wp-content/uploads/import/documents/interpretations/802.3ab-1999_interp.pdf)
· [ANSI/TIA Standards](https://tiaonline.org/)

### Q83. An SFP transceiver shows link down despite being properly seated

*Tier: L2. Safety: read-only.*

**Short answer.** Read the transceiver diagnostics before swapping
hardware. Then think in terms of link budget and PMD compatibility
rather than absolute rules, because the interesting failures are the
marginal ones.

**What is actually going on.** Both ends of an optical link must agree
on the physical medium dependent type, wavelength and fibre type, and
the received power must land inside the receiver's usable window.

Two things go wrong in ways people describe too absolutely:

**Fibre type mismatch.** A single-mode optic launched into multi-mode
fibre is out of specification and should not be relied on. It will
sometimes link over very short distances, which is worse than failing
cleanly because it produces an intermittent link that works during
commissioning and fails later. Mode-conditioning patch cords exist for
specific documented combinations and are not a general workaround.

**Reach class mismatch.** Whether two different reach classes
interoperate depends on launch power, receiver sensitivity, receiver
overload, wavelength and the actual link loss. A long-reach optic
driving a short fibre into a short-reach receiver can *overload* it,
which fails even though there is plenty of light. Attenuators exist
precisely for that case.

So the useful mental model is: compare PMD types, then compare Tx power
against the far end's sensitivity and overload limits, then account for
the loss in between.

**How to check**

                                                         [read-only]
    show interface transceiver detail
      -> type, wavelength, Tx power, Rx power
    show interface <if> transceiver properties
    show logging | include GBIC|SFP|TRANSCEIVER|UNSUPPORTED
    show inventory

    Reading Rx power
      Very low or no light        reversed Tx-Rx, a break, or far-end Tx failed
      Above the overload limit    too much power; add an attenuator
      Within spec, link still down PMD mismatch, encoding, speed, or vendor lock

    Confirm both ends agree on
      PMD type, wavelength (850 / 1310 / 1550 nm), fibre type, reach class

**Watch out for.** Swap the two fibre strands as a first test. Reversed
Tx and Rx costs nothing to check, accounts for a meaningful share of
these tickets, and is especially common right after patching work.

**References:** [IEEE
802.3](https://standards.ieee.org/ieee/802.3/10422/) · [SFF
specifications, diagnostic
monitoring](https://www.snia.org/technology-communities/sff/specifications)

### Q84. Multiple ports on the same switch card show errors after a power event

*Tier: L2. Safety: read-only.*

**Short answer.** Probable hardware damage from the surge or brownout.
Check hardware and diagnostic log messages, run online diagnostics,
review power and environmental status, and plan to replace the affected
line card rather than chase individual ports.

**What is actually going on.** A surge or brownout stresses components
without necessarily destroying them, so the failure shows up as
intermittent errors that get worse over time rather than as a clean
failure.

Multiple ports on the same card failing together points at shared
components, meaning the card's PHY, ASIC or power rail, rather than at
cabling. Cable faults do not correlate by card position.

The operationally important point is that partial hardware failure gets
worse. A card showing post-surge errors should be scheduled for
replacement, not monitored indefinitely and forgotten.

**How to check**

                                                         [read-only]
    show logging | include HARDWARE|DIAG|POWER|ASIC|PARITY
    show diagnostic result module <n> detail
    show module
    show environment all
    show power status
    show interface counters errors      do failures cluster by port group?

    Evidence for hardware rather than cabling
      - errors cluster on one card or one port ASIC group
      - errors persist after moving the cable to a different card
      - diagnostics report failures
      - the error rate is trending upward over days

**Watch out for.** Move a suspect connection to a different line card.
If the errors follow the port rather than the cable, the hardware is
confirmed and the vendor RMA conversation becomes straightforward. Also
check whether the UPS actually held during the event, because an
untested UPS is a common contributing cause that nobody thinks to
verify.

**References:** [IEEE
802.3](https://standards.ieee.org/ieee/802.3/10422/) · [IEEE 1100,
Powering Electronic
Equipment](https://standards.ieee.org/ieee/1100/2237/)

# Part V. Escalation and Professional Practice

These scenarios test judgement, communication and honesty under
pressure. They are answered best with your own experience, framed using
STAR, rather than with memorised process.

## Chapter 10. Escalation, ITIL and Communication

*Scenarios Q85 to Q91. Tier mix: 1 L1, 6 L2.*

### Orientation

**Do not memorise these answers.** Interviewers hear textbook process
answers constantly and discount them within a sentence.

Take the principle from each scenario, then rebuild the answer around an
incident you actually worked, using **STAR**:

- **Situation.** What was happening, briefly.
- **Task.** What you specifically were responsible for.
- **Action.** What you did, in the first person. Not "we," which hides
  your contribution.
- **Result.** What happened, and what changed afterwards.

Prepare three or four real stories in advance and you can adapt them to
almost any behavioural question in this category. A specific account of
a real Friday night outage beats a correct description of change
management every single time.

If you are early in your career and genuinely have no incidents to draw
on, say so honestly and describe how you would approach it. Interviewers
respect that far more than an invented story, and invented stories fall
apart under one follow-up question.

Each scenario below ends with a **STAR prompt** to help you build your
own version.

### Scenarios in this chapter

  ------------------------------------------------------------------------------------------------------------------------------------------------
  ID                                                                                 Scenario                                          Tier
  ---------------------------------------------------------------------------------- ------------------------------------------------- -----------
  [Q85](#q85.-a-vendors-ticket-for-a-circuit-outage-isnt-progressing)                Vendor escalation                                 L2

  [Q86](#q86.-you-suspect-another-teams-change-caused-an-issue-but-they-deny-it)     Cross-team conflict                               L2

  [Q87](#q87.-how-do-you-triage-several-simultaneous-incidents-with-limited-staff)   Triage under load                                 L2

  [Q88](#q88.-a-recurring-issue-keeps-getting-temporary-fixes)                       Problem management                                L2

  [Q89](#q89.-how-do-you-communicate-with-stakeholders-during-a-major-outage)        Stakeholder communication                         L2

  [Q90](#q90.-a-change-you-made-caused-unexpected-downtime.-whats-your-next-step)    Ownership and restoration                         L2

  [Q91](#q91.-how-do-you-stay-aware-of-network-changes-across-departments)           Situational awareness                             L1
  ------------------------------------------------------------------------------------------------------------------------------------------------

### Q85. A vendor's ticket for a circuit outage isn't progressing

*Tier: L2. Safety: read-only.*

**Short answer.** Escalate inside the vendor using their published path
and your contract's SLA terms, quoting the circuit ID and case number.
In parallel, open an internal bridge and progress any workaround
independently, rather than waiting.

**What is actually going on.** Vendor tickets stall for predictable
reasons: the case sat in a queue, it went to the wrong team, or it was
closed as "no fault found" without telling anyone.

Two levers actually move them: the contractual SLA and a named
escalation contact. Knowing both *before* the incident matters far more
than anything you say during it.

Running the workaround in parallel is the part junior engineers skip.
Waiting for a vendor while a redundant path sits unused is a choice, and
usually the wrong one.

**How to work it**

    Escalating effectively
      - reference the circuit ID, case number, and elapsed time
      - state the SLA clause and time remaining or already breached
      - ask for a named engineer and a callback time, not a status
      - request the duty manager if the callback is missed
      - escalate through your account manager in parallel for major outages

    In parallel, internally
      - is there a redundant path? Fail over now, not after they answer
      - keep stakeholders updated on your cadence, not the vendor's
      - log every vendor interaction with a timestamp for the review

**STAR prompt.** Describe a time you escalated to a carrier or vendor.
What evidence did you present, what did you do while waiting, and what
changed as a result?

**Reference:** [ITIL 4 Supplier
Management](https://www.axelos.com/certifications/itil-service-management)

### Q86. You suspect another team's change caused an issue but they deny it

*Tier: L2. Safety: read-only.*

**Short answer.** Present evidence rather than an accusation. Logs and
timestamps correlating the change window with symptom onset, plus the
mechanism you believe links them. Ask for a joint session, and be
explicit that you might be wrong.

**What is actually going on.** Denial is usually genuine belief, not
obstruction. The other team is looking at their own domain, where
everything appears healthy.

Correlation is also not causation, and a confident accusation that turns
out to be wrong damages a working relationship you will need again next
month. Framing it as a shared investigation keeps the other team engaged
and, in practice, gets to the answer faster.

If a rollback is low risk, proposing it as a hypothesis test rather than
as a demand often ends the standoff immediately.

**How to work it**

    Present
      - exact symptom onset time from monitoring
      - exact change window from the change record
      - the correlation, described as correlation, not proof
      - a plausible mechanism linking the two
      - what you have already ruled out on your own side

    Propose
      - a joint session, both teams looking at their own telemetry
      - a controlled test: roll back in a window and observe
      - blameless framing: "help me rule this in or out"

    Avoid
      - accusation in a group channel
      - escalating to management before a technical conversation

**STAR prompt.** Describe a disagreement with another team during an
incident. How did you establish the facts, and what did you do
differently afterwards?

**Reference:** [Google SRE, Postmortem
Culture](https://sre.google/sre-book/postmortem-culture/)

### Q87. How do you triage several simultaneous incidents with limited staff?

*Tier: L2. Safety: read-only.*

**Short answer.** Rank by business impact and affected user count rather
than arrival order, work the highest-impact one first, communicate
realistic timelines for the rest, and ask for extra resource early
rather than after the SLAs are already at risk.

**What is actually going on.** The failure mode under load is context
switching. An engineer bouncing between four incidents finishes none of
them and resolves everything more slowly than if they had worked them in
sequence.

Deliberate sequencing is faster even though it feels worse for whoever
is placed later, which is why communicating the sequencing matters as
much as choosing it.

Quick wins are the legitimate exception. If one incident closes in five
minutes, closing it reduces the queue and the noise, and that is worth
doing out of order.

**How to work it**

    Rank by
      1. Business impact: revenue, safety, regulatory, customer-facing
      2. Number of users affected
      3. Whether impact is expanding or contained
      4. Time already elapsed against SLA
      5. Effort to resolve: a genuine five-minute fix earns queue jumping

    Then
      - one owner per incident; avoid shared ownership
      - communicate the sequencing to stakeholders explicitly
      - request additional resource EARLY, not at the breach point
      - re-rank if impact grows; do not defend the original order out of pride

**STAR prompt.** Describe a shift where you handled several incidents at
once. How did you sequence them, and what did you tell the people whose
incident you deprioritised?

**Reference:** [ITIL 4 Incident
Management](https://www.axelos.com/certifications/itil-service-management)

### Q88. A recurring issue keeps getting temporary fixes

*Tier: L2. Safety: read-only.*

**Short answer.** Raise a formal problem record, separate from the
incident queue, with an owner and time allocated to investigate. Bring
evidence of the cumulative cost, because that is what justifies the
investment.

**What is actually going on.** Incident management restores service.
Problem management removes the cause. They compete for the same people,
and incidents always win because they are urgent. Without a separate
record and separate time, the root cause is never investigated.

The argument that changes minds is quantitative. An incident recurring
weekly and consuming two hours each time costs more over a year than the
permanent fix. Presenting it that way converts a technical preference
into a business case, which is what gets it approved.

**How to work it**

    Build the case
      - frequency and trend over the last three to six months
      - total downtime and total engineer hours consumed
      - business impact per occurrence
      - estimated cost of permanent remediation
      - an explicit comparison of the two numbers

    Then
      - open a problem record with a named owner and a due date
      - allocate investigation time outside the incident queue
      - document the known error and workaround while investigating
      - track to closure, then report the reduction afterwards

**STAR prompt.** Describe a recurring problem you drove to permanent
resolution. How did you justify the time, and what was the measurable
result?

**Reference:** [ITIL 4 Problem
Management](https://www.axelos.com/certifications/itil-service-management)

### Q89. How do you communicate with stakeholders during a major outage?

*Tier: L2. Safety: read-only.*

**Short answer.** Separate the communication role from the engineering
role, publish updates on a fixed cadence through one channel, and lead
with business impact rather than technical detail. State uncertainty
honestly rather than inventing an ETA.

**What is actually going on.** This question often arrives in a specific
form: an executive is demanding constant updates during a major outage.
The demand is legitimate. The interruption pattern is the problem.

Every ad hoc status request costs an engineer context and time, and
during a serious incident those interruptions extend the outage the
executive is asking about. A stated cadence satisfies the underlying
need, which is confidence that the situation is under control, not raw
technical detail. Updates delivered on schedule even when nothing has
changed are what build that confidence.

The content matters as much as the rhythm. Non-technical stakeholders
need four things: what is broken from their perspective, how long it
will last, what is being done, and when they will hear next. Technical
detail offered unprompted signals you are more interested in the problem
than in the audience.

Analogies help when they are accurate and hurt when they are strained.
Use one only if it survives a follow-up question.

**How to work it**

    Structure
      Incident Manager        owns the incident, makes decisions
      Incident Communicator   owns all stakeholder updates
      Technical lead          owns the fix, fields no status requests

    Update format, every 15 to 20 minutes
      1. Impact:    "Users at the Birmingham office cannot access email or files."
      2. Scope:     "About 200 people. Other sites are unaffected."
      3. Cause:     "The main internet circuit to that office has failed."
      4. Action:    "The carrier is engaged; we are moving to the backup link."
      5. Timeline:  "Backup should restore service within 30 minutes."
      6. Next:      "I will update you at 14:20 either way."

    Avoid
      jargon, invented ETAs, unrequested technical detail

**Watch out for.** Never invent an ETA under pressure. "We do not have a
reliable estimate yet; the next update is at 14:20" preserves
credibility. A missed invented ETA destroys it, and you will need that
credibility for the rest of the incident.

**STAR prompt.** Describe explaining a serious technical failure to a
senior non-technical stakeholder. What did you include, what did you
leave out, and how did they respond?

**Reference:** [ITIL 4 Incident
Management](https://www.axelos.com/certifications/itil-service-management)

### Q90. A change you made caused unexpected downtime. What's your next step?

*Tier: L2. Safety: change approval.*

**Short answer.** Stop the change, invoke incident and change authority,
and restore service by the safest available means according to the
approved decision criteria. In most cases that is the pre-approved
rollback, but not always. Then notify stakeholders promptly and
honestly.

**What is actually going on.** Two things are being tested here, and
only one of them is technical.

The technical judgement is about restoration. "Roll back immediately" is
the right instinct most of the time, and diagnosing before restoring
extends the outage while you satisfy your curiosity. But rollback is not
universally safe or even available:

- A firmware upgrade or a schema migration may not be cleanly reversible
- Rolling back may itself require a reload and extend the outage
- Partial rollback can leave the system in a state neither version
  expects
- If the change has already been partly consumed by other systems,
  reverting can cause a second, larger failure

So the correct framing is: restore service by the safest available
means, using the rollback decision criteria that were agreed *before*
the window opened. Sometimes a controlled forward fix genuinely is lower
risk, and a senior engineer is expected to make that call with the
change authority rather than alone.

The second thing being tested is disclosure. Attempting to fix quietly
and hoping nobody noticed is the answer that ends interviews. Prompt,
plain disclosure is what a mature organisation expects and what a
blameless culture exists to make safe.

**How to work it**

    Order of operations
      1. Stop the change. Make no further modifications.
      2. Declare the incident and engage change authority.
      3. Restore service by the safest available means:
           - pre-approved rollback, if it is available and safe
           - controlled forward fix, if rollback is riskier
           - failover to a redundant path, if one exists
      4. Verify restoration end to end, as a user would.
      5. Notify stakeholders: what happened, current state, next steps.
      6. Preserve evidence: logs, config diffs, timestamps.
      7. Update the change record with the actual outcome.
      8. Blameless review: why was this risk not identified at approval?

    Do not
      - attempt an unplanned forward fix alone, under pressure
      - conceal or minimise the cause
      - close the change as successful

**STAR prompt.** Describe a change you made that caused an outage. What
did you do in the first five minutes, how did you decide between
rollback and forward fix, and what control did you add afterwards?

**References:** [ITIL 4 Change
Enablement](https://www.axelos.com/certifications/itil-service-management)
· [Google SRE, Postmortem
Culture](https://sre.google/sre-book/postmortem-culture/)

### Q91. How do you stay aware of network changes across departments?

*Tier: L1. Safety: read-only.*

**Short answer.** Review the change calendar and CAB notifications as
routine, keep a shift handover log that carries context forward, and
build change visibility into the incident workflow so checking is a
required step rather than a good habit.

**What is actually going on.** Change awareness fails when it depends on
individual diligence. Making it a process step is what makes it
reliable.

The strongest control is automated configuration-diff alerting, because
it catches changes nobody declared. The changes that cause outages are
disproportionately the ones that bypassed the process, and those are
exactly the ones a calendar will never show you.

**How to work it**

    Routine
      - change calendar reviewed at the start of every shift
      - NOC on the distribution list for all CAB notifications
      - shift handover log carrying open items and recent changes forward
      - a short daily standup covering the next 24 hours of planned work

    Systematic
      - automated configuration-diff alerting on all network devices
      - "changes in the last 24h checked" as a required incident field
      - change timestamps correlated automatically against alert timestamps
      - relationships with the teams whose changes affect you, built before
        you need them

**STAR prompt.** Describe a time an undeclared change caused an
incident. What did you change about how your team maintained awareness
afterwards?

**Reference:** [ITIL 4 Change
Enablement](https://www.axelos.com/certifications/itil-service-management)

# Part VI. Hosts, Supporting Protocols and IPv6

Part VI covers the faults that sit just outside the network but get
reported as network problems: host routing and firewalls, time and
monitoring protocols, and the IPv6 behaviour that many dual-stack
networks enable without planning for.

## Chapter 11. Server and OS Networking

*Scenarios Q92 to Q96. Tier mix: 5 L2.*

### Orientation

A large share of "network" tickets turn out to be host problems, and a
NOC engineer who can prove that quickly saves everyone a lot of arguing.

Three host-side concepts are worth understanding because they cause
faults that look exactly like network faults:

**The host has its own routing table.** A server can be perfectly
connected and still fail to reach anything because it has no default
route or the wrong one.

**The host has its own firewall.** iptables, nftables, firewalld and
Windows Defender Firewall all drop traffic that arrived over a healthy
network.

**Multi-homed hosts behave differently by operating system.** Linux and
Windows make different assumptions about which interface owns an address
and which one replies. Those differences cause genuinely confusing,
intermittent faults.

One command is worth memorising: `ip`` route get <destination>` on Linux
tells you exactly which route and which source address the kernel will
use. It answers in one line what reading the routing table and reasoning
about it takes several minutes to work out.

### Scenarios in this chapter

  -------------------------------------------------------------------------------------------------------------------------------------------------------
  ID                                                                                       Scenario                                             Tier
  ---------------------------------------------------------------------------------------- ---------------------------------------------------- ---------
  [Q92](#q92.-a-linux-server-can-ping-its-gateway-but-not-any-other-host)                  Host routing and filtering                           L2

  [Q93](#q93.-a-windows-server-loses-connectivity-right-after-an-update)                   Driver and firewall profile                          L2

  [Q94](#q94.-two-nics-on-a-server-in-the-same-subnet-cause-intermittent-connectivity)     Multi-homing behaviour                               L2

  [Q95](#q95.-a-servers-throughput-is-capped-well-below-the-nics-rated-speed)              Host throughput                                      L2

  [Q96](#q96.-a-hostname-resolves-fine-but-tls-certificate-errors-happen-intermittently)   Certificates behind load balancing                   L2
  -------------------------------------------------------------------------------------------------------------------------------------------------------

### Q92. A Linux server can ping its gateway but not any other host

*Tier: L2. Safety: read-only.*

**Short answer.** Reaching the gateway shows the local interface, ARP
and the local segment are working for ICMP. The fault is beyond the
local subnet: routing, host filtering, or reverse path filtering.

**What is actually going on.** Local subnet traffic needs only ARP and a
correct interface address. Anything beyond it needs a route.

A missing or badly weighted default route is the most common cause,
particularly on a multi-homed host or after a NetworkManager change.
Host firewalls are next: a default DROP on OUTPUT, or a rule set
permitting established connections while denying new outbound ones,
produces exactly this.

Reverse path filtering is the subtler third cause on multi-homed hosts.
The kernel drops replies that would leave by a different interface than
the one they arrived on, which looks like the network dropping traffic
and is not.

**How to check**

                                                        # [read-only]
    ip route show                     # default route present? right interface?
    ip route get 8.8.8.8              # which route will actually be used?
    ip addr show
    ip neigh show                     # ARP: is the gateway resolved?

    iptables -L -v -n                 # legacy
    nft list ruleset                  # nftables
    firewall-cmd --list-all           # firewalld

    sysctl net.ipv4.conf.all.rp_filter
    sysctl net.ipv4.ip_forward        # only relevant if it should route

                                      # [active test]
    traceroute -n 8.8.8.8

**Watch out for.** `ip`` route get` also shows the source address the
kernel will select. On a multi-homed host that is frequently the actual
problem, because the reply comes from an address the far end did not
expect.

**References:** [RFC 1122, Requirements for Internet
Hosts](https://www.rfc-editor.org/rfc/rfc1122.html) · [Linux
ip-route(8)](https://man7.org/linux/man-pages/man8/ip-route.8.html)

### Q93. A Windows server loses connectivity right after an update

*Tier: L2. Safety: read-only.*

**Short answer.** Two leading candidates. A NIC driver replaced by the
update, losing offload, VLAN or teaming settings. Or the network profile
no longer being recognised as the domain network, so a more restrictive
firewall profile applies.

**What is actually going on.** Windows Update can replace a working
vendor NIC driver with a generic one, which sometimes drops advanced
settings including teaming configuration.

The profile issue needs care, because the popular "fix" for it does not
work. Windows assigns the domain profile automatically when Network
Location Awareness successfully authenticates against a domain
controller. You cannot simply force that assignment with a cmdlet, and
attempting to set the domain category manually fails.

So when a server drops into the Public profile after an update, the
profile is a *symptom*. The real question is why the machine could not
contact a domain controller at boot, which usually means the NIC
initialised after Network Location Awareness ran, or DNS was not
answering yet, or the driver problem above delayed the interface.

Fixing DNS and domain controller reachability restores the correct
profile on its own.

**How to check**

                                                        # [read-only]
    Get-NetAdapter | Select Name, Status, LinkSpeed, DriverVersion, DriverDate
    Get-NetConnectionProfile                # Domain, Private, or Public?
    Get-NetFirewallProfile | Select Name, Enabled
    Get-NetAdapterAdvancedProperty -Name "Ethernet"
    Get-NetLbfoTeam                         # did teaming survive the update?

    # Why is it not identifying the domain network?
    Test-NetConnection <domain-controller> -Port 389
    Resolve-DnsName <domain-fqdn>
    nltest /dsgetdc:<domain>

    # Recent updates
    Get-HotFix | Sort InstalledOn -Descending | Select -First 10
    Remediation                                          [change approval]
      - roll the NIC driver back (Device Manager > Driver > Roll Back Driver)
      - fix DNS and domain controller reachability, then restart
        the Network Location Awareness service so the profile re-evaluates
      - re-apply teaming and advanced adapter settings if they were lost

**Watch out for.** On a server with teamed NICs, check whether the team
survived at all. Driver replacement can silently break teaming and leave
the server on a single adapter. Everything works fine until the day that
adapter's switch is rebooted, and then it does not.

**Reference:** [Microsoft, domain profile detection
troubleshooting](https://learn.microsoft.com/en-us/troubleshoot/windows-client/networking/domain-joined-machines-cannot-detect-domain-profile)

### Q94. Two NICs on a server in the same subnet cause intermittent connectivity

*Tier: L2. Safety: read-only.*

**Short answer.** Two interfaces in one broadcast domain create
ambiguity in which interface sends, which one replies, and which address
the far end sees. Team or bond them, or move one to a different subnet.
Two independent NICs in one subnet is a misconfiguration, not a
redundancy design.

**What is actually going on.** The common explanation of the mechanism
is wrong. Two independent NICs have two different MAC addresses, so you
will not normally see one MAC flapping between switch ports. That is
what happens with a Layer 2 loop, not with this.

What actually goes wrong is operating system dependent:

**On Linux (weak host model by default).** Any interface will answer an
ARP request for any local address, so the far end may learn either MAC
for the address it wants. This is ARP flux. The reply may then leave by
the other interface entirely, and source address selection may pick an
address the far end did not send to. `arp_ignore` and `arp_announce`
control this behaviour, and reverse path filtering may then drop the
return traffic.

**On Windows (strong host model since Vista).** An interface will not
accept traffic for an address bound to a different interface, which
prevents some of the Linux behaviour but introduces its own: outbound
traffic follows interface metric, and a reply can leave via the
interface with the better metric rather than the one the request arrived
on, producing asymmetry that stateful devices drop.

**On both.** Two default gateways in the same subnet gives you two
equally valid exit paths and no deterministic choice, which is where the
intermittency comes from.

**How to check**

    Linux                                                [read-only]
      ip route show                        two routes to the same subnet?
      ip route get <remote-host>           which interface and source address?
      sysctl net.ipv4.conf.all.arp_ignore
      sysctl net.ipv4.conf.all.arp_announce
      sysctl net.ipv4.conf.all.rp_filter
      cat /proc/net/bonding/bond0          if bonded

    Windows                                              [read-only]
      Get-NetIPInterface | Sort InterfaceMetric
      Get-NetRoute -DestinationPrefix 0.0.0.0/0    two default gateways?
      Get-NetLbfoTeam                              is teaming configured?

    From the far end                                     [read-only]
      arp -a <server-ip>                   which MAC did it learn?
      Does the answer change over time?
    Correct designs                                      [change approval]
      1. NIC teaming or bonding: one logical interface, one MAC, one address
      2. Two interfaces in genuinely different subnets, with deliberate routing
         and a single default gateway

**Watch out for.** Say explicitly that dual-homing into the same subnet
without teaming is a misconfiguration rather than a redundancy strategy.
That framing is what the interviewer is checking for, and it is more
useful than reciting sysctl names.

**References:** [RFC 826,
ARP](https://www.rfc-editor.org/rfc/rfc826.html) · [IEEE 802.1AX, Link
Aggregation](https://standards.ieee.org/ieee/802.1AX/7404/)

### Q95. A server's throughput is capped well below the NIC's rated speed

*Tier: L2. Safety: active test.*

**Short answer.** Work down the stack: negotiated speed and duplex,
offload settings, virtual switch or hypervisor limits, CPU saturation on
a single queue, then the TCP stack itself. Measure with iperf3 before
and after each change so you know what actually helped.

**What is actually going on.** Several unrelated bottlenecks produce the
same symptom.

A half-duplex negotiation caps throughput and generates late collisions.
Disabled offloads push per-packet work onto the CPU, and a single
saturated core limits the whole interface. In virtualised environments
the vSwitch, port group or a hypervisor shaping policy can cap a VM
regardless of the guest configuration.

On high-latency paths the limit may not be the host at all. If the TCP
window is too small for the bandwidth-delay product, the pipe never
fills and no amount of NIC tuning changes that.

**How to check**

                                                        # [read-only]
    ethtool eth0                     # negotiated speed and duplex
    ethtool -k eth0                  # offload settings
    ethtool -S eth0                  # per-queue drops and errors
    ethtool -g eth0                  # ring buffer sizes
    mpstat -P ALL 1                  # is one core pinned at 100 percent?
    ss -ti                           # cwnd, rtt, retransmits per socket
    sysctl net.core.rmem_max net.ipv4.tcp_rmem

                                     # [active test]
    iperf3 -c <server> -t 30         # single stream
    iperf3 -c <server> -t 30 -P 8    # parallel streams
    Bandwidth-delay product
      required window (bytes) = bandwidth (bits/s) x RTT (seconds) / 8
      Example: 1 Gbps at 80 ms RTT needs roughly a 10 MB window

**Watch out for.** Compare single-stream against parallel-stream
results. If eight streams reach line rate and one does not, the limit is
per-flow, meaning window size, a single CPU queue, or a shaper, and not
the interface itself.

**References:** [RFC 6349, TCP Throughput
Testing](https://www.rfc-editor.org/rfc/rfc6349.html) · [RFC 7323, TCP
Extensions for High
Performance](https://www.rfc-editor.org/rfc/rfc7323.html)

### Q96. A hostname resolves fine but TLS certificate errors happen intermittently

*Tier: L2. Safety: active test.*

**Short answer.** The name resolves to more than one server and they are
not all presenting the same certificate, or one node holds a stale or
expired one. Test each backend individually rather than through the
load-balanced name.

**What is actually going on.** DNS round robin or a load balancer
spreads connections across several nodes. A client reaching a node with
a correct certificate succeeds; a client reaching a node with an
expired, renamed or not-yet-renewed certificate fails. The intermittency
is proportional to how many nodes are wrong.

Related causes look similar: a Subject Alternative Name list that omits
one of the names clients use, so failure depends on which name was
requested; SNI misconfiguration on a shared listener returning the
default certificate; and a missing intermediate on one node only, which
fails for clients that have not cached that intermediate.

**How to check**

    # Find every backend, then test each one directly     # [active test]
    dig +short server.example.com

    for ip in 10.1.1.10 10.1.1.11 10.1.1.12; do
      echo "== $ip"
      openssl s_client -connect $ip:443 -servername server.example.com \
        </dev/null 2>/dev/null \
        | openssl x509 -noout -serial -subject -dates -ext subjectAltName
    done
    Check on every node
      [ ] Same certificate, same serial number
      [ ] Not expired, and not renewed on only some nodes
      [ ] SAN list covers every hostname clients use
      [ ] Full chain served, including intermediates
      [ ] SNI configured so the right certificate is selected

**Watch out for.** Comparing serial numbers across backends finds the
odd node in seconds. Testing through the load-balanced name is
unreliable because you cannot control which backend you reach, and you
may test the healthy ones five times in a row and conclude nothing is
wrong.

**References:** [RFC 5280, X.509 Certificate
Profile](https://www.rfc-editor.org/rfc/rfc5280.html) · [RFC 6125,
Service Identity](https://www.rfc-editor.org/rfc/rfc6125.html) · [RFC
6066, TLS Extensions](https://www.rfc-editor.org/rfc/rfc6066.html)

## Chapter 12. Miscellaneous Protocols

*Scenarios Q97 to Q101. Tier mix: 4 L2, 1 L3.*

### Orientation

These are the protocols that quietly hold everything else together, and
they tend to fail in ways that look like something else entirely.

**Time** breaks authentication. Kerberos and TLS both compare
timestamps, so a clock that drifts far enough produces "access denied"
and "certificate invalid," not "your clock is wrong."

**SNMP** is how most monitoring reads device state. Change a community
string or an ACL and your monitoring goes dark while the network is
perfectly healthy.

**Email and FTP** are old protocols with unusual connection patterns
that firewalls handle awkwardly.

The habit that helps most here: when a symptom seems disproportionate to
the change that preceded it, look for a dependency you have not
considered. Time is the classic one.

### Scenarios in this chapter

  ----------------------------------------------------------------------------------------------------------------------------------------------------
  ID                                                                                      Scenario                                           Tier
  --------------------------------------------------------------------------------------- -------------------------------------------------- ---------
  [Q97](#q97.-users-complain-email-is-delayed-by-up-to-an-hour-but-eventually-delivers)   SMTP retry behaviour                               L2

  [Q98](#q98.-ftp-fails-in-passive-mode-through-the-firewall-but-works-in-active-mode)    FTP data channels                                  L2

  [Q99](#q99.-ntp-sync-failures-are-causing-certificate-and-authentication-errors)        Time as a dependency                               L2

  [Q100](#q100.-snmp-polling-fails-for-a-subset-of-devices-after-a-hardening-project)     Monitoring credentials and ACLs                    L2

  [Q101](#q101.-one-particular-tcp-port-randomly-fails-while-others-work)                 Intermittent connection failure                    L3
  ----------------------------------------------------------------------------------------------------------------------------------------------------

### Q97. Users complain email is delayed by up to an hour but eventually delivers

*Tier: L2. Safety: read-only.*

**Short answer.** Delivery that is delayed but eventually succeeds
points at retry behaviour: greylisting, a queue backlog, or DNS failures
forcing retries. Read the message headers, because each hop stamps its
own time and the gap tells you exactly where the delay was.

**What is actually going on.** Greylisting deliberately rejects the
first delivery attempt from an unknown sender with a temporary failure,
on the assumption that legitimate mail servers retry and spam sources do
not. Retry intervals of 15 to 60 minutes match the reported symptom
precisely.

Queue backlogs from a rate limit or reputation throttle look similar. So
do DNS failures: if the sender cannot resolve the recipient's MX record,
or the receiver cannot resolve SPF for the sender, delivery is deferred
and retried.

The headers separate these cleanly, which is why they are the first
thing to read rather than the last.

**How to check**

    Read the message headers                             [read-only]
      Each "Received:" line carries a timestamp.
      The gap between two consecutive hops is where the delay lives.

    Sending side                                         [read-only]
      Exchange:   Get-Queue ; Get-MessageTrackingLog -MessageId <id>
      Postfix:    postqueue -p ; grep <message-id> /var/log/mail.log

    DNS                                                  [active test]
      dig MX example.com
      dig TXT example.com          SPF record present and valid?
      dig -x <sending-ip>          does reverse DNS match the HELO name?

    Look for 4xx temporary rejections in the logs.
    That is greylisting or throttling, stated explicitly.

**Watch out for.** Missing or mismatched reverse DNS on the sending IP
triggers greylisting and throttling at many receivers. It is a
frequently overlooked cause of exactly this symptom, so check PTR
alongside SPF rather than only SPF.

**References:** [RFC 5321,
SMTP](https://www.rfc-editor.org/rfc/rfc5321.html) · [RFC 6647, Email
Greylisting](https://www.rfc-editor.org/rfc/rfc6647.html) · [RFC 7208,
SPF](https://www.rfc-editor.org/rfc/rfc7208.html)

### Q98. FTP fails in passive mode through the firewall but works in active mode

*Tier: L2. Safety: read-only.*

**Short answer.** The firewall is not handling the data connection for
that mode. Active and passive open the data channel in opposite
directions on dynamic ports, so each needs different handling. Either
enable the FTP inspection engine, or define a fixed passive port range
and permit it explicitly.

**What is actually going on.** FTP separates control and data. The
control channel uses TCP 21 in both modes.

  ---------------------------------------------------------------------------
  Mode      Data connection                Blocked by
  --------- ------------------------------ ----------------------------------
  Active    Server port 20 connects back   Client-side firewalls, as an
            to the client's high port      unsolicited inbound connection

  Passive   Client connects to a high port Server-side firewalls, if the
            on the server                  dynamic range is not permitted
  ---------------------------------------------------------------------------

An application layer gateway reads the control channel and opens the
pinhole dynamically. That works right up until someone encrypts the
control channel with FTPS, at which point the gateway can no longer read
it and the whole mechanism fails.

**How to check**

    Server side, passive                                 [change approval]
      vsftpd:  pasv_min_port=50000 ; pasv_max_port=50100
      IIS:     set the passive port range, then permit it on the firewall

    Firewall                                             [read-only]
      show service-policy inspect ftp        Cisco ASA
      Permit the fixed passive range explicitly if inspection is disabled

    Diagnose                                             [active test]
      ftp -d <server>                        verbose: watch PORT vs PASV
      tcpdump -i <if> -n port 21             read the PASV response

**Watch out for.** Inspection engines cannot see inside FTPS, so an
encrypted FTP deployment must use a fixed passive port range with
explicit rules. It also illustrates why application layer gateways are
falling out of favour generally.

**References:** [RFC 959,
FTP](https://www.rfc-editor.org/rfc/rfc959.html) · [RFC 2428, FTP
Extensions for NAT](https://www.rfc-editor.org/rfc/rfc2428.html) · [RFC
4217, Securing FTP with
TLS](https://www.rfc-editor.org/rfc/rfc4217.html)

### Q99. NTP sync failures are causing certificate and authentication errors

*Tier: L2. Safety: read-only.*

**Short answer.** Clock drift beyond tolerance. Kerberos rejects tickets
outside a default five-minute skew, and TLS validation compares the
certificate validity window against the local clock. Verify NTP
reachability, stratum and offset, then fix the time hierarchy.

**What is actually going on.** Time is a dependency of authentication
and encryption, so a time failure presents as a security failure. That
is why it gets diagnosed slowly.

Kerberos includes timestamps specifically to prevent replay and enforces
a tolerance, commonly five minutes. Exceed it and authentication fails
across the domain. TLS validation fails if the local clock sits outside
the certificate's validity period, which is why a device with a dead
battery and a clock reset to 1970 rejects every certificate it sees.

Common causes: UDP 123 blocked, a stratum loop where devices synchronise
to each other rather than to an authoritative source, and virtual
machines where host time sync and in-guest NTP fight each other.

**How to check**

    Cisco                                                [read-only]
      show ntp status                  synchronised? stratum? offset?
      show ntp associations detail
      show clock detail

    Linux                                                [read-only]
      timedatectl status
      chronyc tracking ; chronyc sources -v
      ntpq -p

    Windows                                              [read-only]
      w32tm /query /status
      w32tm /query /source
      w32tm /stripchart /computer:<dc> /samples:5

    Confirm
      [ ] UDP 123 permitted to the time source
      [ ] Stratum is sane; 16 means unsynchronised
      [ ] Offset well within tolerance
      [ ] One authoritative hierarchy, not devices syncing to each other
      [ ] VMs: host time sync and guest NTP not both enabled

**Watch out for.** In a Windows domain, time flows from the PDC emulator
down through the hierarchy, and that server should be the only one
synchronising externally. Domain members pointed straight at an internet
time source is a common misconfiguration that causes quiet, intermittent
authentication failures.

**References:** [RFC 5905,
NTPv4](https://www.rfc-editor.org/rfc/rfc5905.html) · [RFC 4120,
Kerberos V5](https://www.rfc-editor.org/rfc/rfc4120.html)

### Q100. SNMP polling fails for a subset of devices after a hardening project

*Tier: L2. Safety: read-only.*

**Short answer.** The hardening changed SNMP on those devices. Community
strings rotated, the version moved to v3, or a new ACL restricts which
sources may poll. Work out what the failing subset has in common,
because that names the change.

**What is actually going on.** SNMP hardening typically does three
things, and any of them breaks polling if the monitoring platform is not
updated in step:

- **Community strings rotated.** v1 and v2c strings travel in clear
  text, so rotating them is genuinely worthwhile, and forgetting to tell
  monitoring is genuinely common.
- **Version moved to v3**, which needs authentication and privacy
  credentials the monitoring system must be given.
- **An ACL applied** restricting SNMP to specific sources, which fails
  if the monitoring server polls from a different address than the one
  documented.

The "subset" detail is the clue. Whatever those devices share, a
template, a site, a platform, is where the change landed.

**How to check**

    Device                                               [read-only]
      show snmp
      show snmp community
      show snmp user
      show snmp group
      show run | include snmp-server

    From the monitoring server                           [active test]
      snmpwalk -v2c -c <community> <device> system
      snmpwalk -v3 -l authPriv -u <user> -a SHA -A <authpass> \
               -x AES -X <privpass> <device> system

    Reconcile
      [ ] Version matches on both sides
      [ ] Credentials match exactly, including case
      [ ] The ACL permits the monitoring server's ACTUAL source address
      [ ] The correct VRF is specified if management sits in a VRF

**Watch out for.** A monitoring server with several interfaces may poll
from a different source than the one in the ACL. Confirm the actual
source with a capture on the device rather than trusting documentation,
because that mismatch is invisible from both ends until you look at the
packets.

Also: do not paste live community strings or v3 credentials into tickets
or chat. Reference the credential store instead.

**References:** [RFC 3411, SNMP Management
Frameworks](https://www.rfc-editor.org/rfc/rfc3411.html) · [RFC 3414,
SNMPv3 USM](https://www.rfc-editor.org/rfc/rfc3414.html)

### Q101. One particular TCP port randomly fails while others work

*Tier: L3. Safety: active test.*

**Short answer.** Capture at both ends simultaneously and compare. The
packet evidence narrows the field considerably, but treat each
observation as an interpretation that needs corroboration rather than as
proof on its own.

**What is actually going on.** Randomness is itself diagnostic.
Consistent failure is policy. Random failure is state, capacity, or path
variation.

The evidence maps to hypotheses like this, and the caveats matter:

  ------------------------------------------------------------------------
  Observation       Leading              But also consider
                    interpretation       
  ----------------- -------------------- ---------------------------------
  SYN never arrives Path drop: firewall, ECMP with one bad path; capture
  at the server     ACL, routing         missing offloaded traffic

  SYN arrives,      Nothing listening at A host firewall configured to
  server sends RST  that instant         REJECT rather than DROP; a
                                         middlebox forging RST

  SYN arrives, no   Listen backlog full, SYN cookies changing behaviour
  response at all   or host firewall     under load; capture placed after
                    DROP                 the drop point

  Handshake         Stateful timeout or  Idle timers on an intermediate
  completes,        application close    device; application crash
  session dies                           

  Fails roughly 1   N backends, one      N ECMP paths, one broken
  in N attempts     unhealthy            
  ------------------------------------------------------------------------

Captures themselves can mislead. Hardware offload can hide traffic from
a host capture, and a capture taken at the wrong point in the path shows
you a clean stream while the drop happens elsewhere. Corroborate with
counters and logs from the devices in between.

**How to check**

    # Simultaneous capture, both ends                     # [active test]
    tcpdump -i any -n "host <client> and port <port>" -w server.pcap
    tcpdump -i any -n "host <server> and port <port>" -w client.pcap

    # Server-side state                                   # [read-only]
    ss -ltnp | grep <port>
    ss -s                              # socket summary, TIME_WAIT volume
    netstat -s | grep -i -E "listen|overflow|drop"
    dmesg | grep -i "possible SYN flooding"
    cat /proc/sys/net/core/somaxconn
    ulimit -n                          # file descriptor limit

**Watch out for.** Listen backlog overflow is under-diagnosed. It
appears in `netstat -s` as listen queue overflows, produces exactly this
intermittent pattern under load, and is invisible to every network-side
test. Naming it demonstrates real depth, because most candidates never
get past the firewall hypothesis.

**References:** [RFC 9293,
TCP](https://www.rfc-editor.org/rfc/rfc9293.html) · [RFC 5382, NAT
Requirements for TCP](https://www.rfc-editor.org/rfc/rfc5382.html)

## Chapter 13. IPv6

*Scenarios Q102 to Q108. Tier mix: 2 L1, 3 L2, 2 L3.*

### Orientation

IPv6 is not "IPv4 with longer addresses." Several things work
differently in ways that produce faults you will not recognise from IPv4
experience, and it comes up increasingly often in interviews because
most candidates have not studied it.

The four differences that matter most operationally:

**There is no ARP.** Neighbour Discovery replaces it, and it runs over
ICMPv6. Which leads directly to the next point.

**You cannot block ICMPv6.** In IPv4, filtering ICMP is merely unwise.
In IPv6 it breaks the protocol: address resolution, router discovery,
duplicate address detection and path MTU discovery all depend on it.
Blanket-blocking ICMPv6 is one of the most common self-inflicted IPv6
outages.

**Hosts usually have several addresses at once.** A link-local address
starting `fe``80::`, one or more global addresses, and often a temporary
privacy address that changes. "The server's IPv6 address" is rarely one
thing.

**Routers advertise themselves.** Instead of DHCP handing out a gateway,
routers send Router Advertisements and hosts listen. That is convenient
and it means any device on the segment can claim to be a router.

**One habit worth building now:** whenever you troubleshoot a dual-stack
service, establish which protocol the client actually used before
anything else. Half of all "dual-stack" tickets are IPv6 problems being
reported as general slowness, because the client tried IPv6 first and
fell back.

### Scenarios in this chapter

  ---------------------------------------------------------------------------------------------------------------------------------------------------------------
  ID                                                                                                 Scenario                                           Tier
  -------------------------------------------------------------------------------------------------- -------------------------------------------------- ---------
  [Q102](#q102.-a-website-is-slow-to-load-for-some-users-but-fine-for-others-on-the-same-network)    Dual-stack fallback delay                          L2

  [Q103](#q103.-clients-have-an-ipv6-address-but-no-ipv6-connectivity)                               RA and default route                               L1

  [Q104](#q104.-users-on-one-vlan-suddenly-lose-connectivity-after-someone-plugs-in-a-home-router)   Rogue Router Advertisement                         L2

  [Q105](#q105.-clients-get-an-ipv6-address-but-no-dns-server)                                       SLAAC, DHCPv6 and the M/O flags                    L2

  [Q106](#q106.-ipv6-connections-hang-on-large-transfers-while-small-requests-work)                  ICMPv6 filtering and PMTUD                         L3

  [Q107](#q107.-a-service-you-firewalled-off-is-still-reachable)                                     Dual-stack policy asymmetry                        L3

  [Q108](#q108.-a-hostname-returns-an-aaaa-record-but-the-service-is-unreachable)                    Premature AAAA publication                         L1
  ---------------------------------------------------------------------------------------------------------------------------------------------------------------

### Q102. A website is slow to load for some users but fine for others on the same network

*Tier: L2. Safety: active test.*

**Short answer.** Suspect a broken IPv6 path with the client falling
back to IPv4 after a delay. Test both protocols separately, because a
dual-stack client hides the failure by eventually succeeding.

**What is actually going on.** Modern clients implement Happy Eyeballs.
They start the IPv6 connection first and, if it has not completed after
a short delay (RFC 8305 recommends 250 ms), start IPv4 in parallel and
use whichever connects first. On such a client a broken IPv6 path costs
a fraction of a second per connection, which adds up on a page that
opens many connections. Multi-second stalls point elsewhere: an
application or older client that does not implement Happy Eyeballs and
waits for a full TCP timeout, or an IPv6 path where the handshake
succeeds and full-size packets then disappear (see
[Q106](#q106.-ipv6-connections-hang-on-large-transfers-while-small-requests-work)).
Happy Eyeballs cannot help in that second case, because the connection
already looked healthy.

That produces a very specific signature: the page eventually loads, so
nobody reports it as an outage, but it feels sluggish. Users on
IPv4-only clients on the same network are unaffected, which makes it
look random.

The underlying IPv6 fault could be almost anything: a route missing at
the ISP, a firewall rule that exists for IPv4 and not IPv6, an MTU
problem, or a AAAA record published for a service that is not actually
listening on IPv6.

**How to check**

                                                        # [active test]
    curl -6 -v -o /dev/null -w '%{time_total}\n' https://example.com
    curl -4 -v -o /dev/null -w '%{time_total}\n' https://example.com
    #   compare the two. A large gap is your answer.

    dig AAAA example.com
    dig A example.com
    ping6 example.com
    traceroute6 example.com
    mtr -6 -rwc 100 example.com
    On the client                                        [read-only]
      ip -6 addr show
      ip -6 route show
      Get-NetIPConfiguration                             Windows

**Watch out for.** Always test with `-6` and `-4` explicitly. A plain
`curl` or browser test succeeds and tells you nothing, because the
fallback is doing its job. Isolating the protocol is the first and most
important step.

**References:** [RFC 8305, Happy Eyeballs Version
2](https://www.rfc-editor.org/rfc/rfc8305.html) · [RFC 6724, Address
Selection for IPv6](https://www.rfc-editor.org/rfc/rfc6724.html)

### Q103. Clients have an IPv6 address but no IPv6 connectivity

*Tier: L1. Safety: read-only.*

**Short answer.** Check which kind of address they have. If it only
starts with `fe``80::`, they have a link-local address and nothing more,
which means no Router Advertisement is reaching them. If they have a
global address but no default route, the RA is arriving without the
router flag set properly.

**What is actually going on.** Every IPv6 interface generates a
link-local address automatically, whether or not anything else is
configured. Seeing an IPv6 address is therefore not evidence of IPv6
working, which trips people up constantly.

A global address requires a Router Advertisement carrying a prefix. The
default route comes from the RA's router lifetime field, and if that is
zero the host installs the prefix but no gateway.

Common causes: IPv6 not enabled on the router interface, RAs suppressed
on that interface, RAs blocked somewhere on the Layer 2 path, or the
router advertising a prefix while not offering itself as a default
router.

**How to check**

    Client                                               [read-only]
      ip -6 addr show
        fe80:: only        -> no RA is being received
        global address     -> RA received, check the route next
      ip -6 route show
        no "default via"   -> RA has a zero router lifetime, or none received

      Get-NetIPAddress -AddressFamily IPv6                Windows
      Get-NetRoute -AddressFamily IPv6

    Router                                               [read-only]
      show ipv6 interface <if>
        is IPv6 enabled? is RA suppressed? what lifetime is advertised?
      show ipv6 routers                                   what is being seen?

                                                         [active test]
      tcpdump -i <if> -n 'icmp6 && ip6[40] == 134'        capture RAs

**Watch out for.** `fe``80::` addresses only ever work on the local
link. A host with nothing else has no IPv6 connectivity at all,
regardless of how healthy the interface looks. Knowing that distinction
is the L1 answer here.

**References:** [RFC 4861, Neighbor Discovery for
IPv6](https://www.rfc-editor.org/rfc/rfc4861.html) · [RFC 4862, IPv6
Stateless Address
Autoconfiguration](https://www.rfc-editor.org/rfc/rfc4862.html)

### Q104. Users on one VLAN suddenly lose connectivity after someone plugs in a home router

*Tier: L2. Safety: read-only.*

**Short answer.** A rogue Router Advertisement. The device is announcing
itself as an IPv6 router, hosts on the segment accept it, and traffic is
black-holed to a device that cannot forward it. Find the source MAC from
a capture, trace it to a switchport, and shut the port.

**What is actually going on.** Hosts accept Router Advertisements from
any device on the link by default. There is no authentication in the
base protocol.

A consumer router plugged in the wrong way round happily advertises a
prefix and offers itself as a default gateway. Hosts configure a global
address from the bogus prefix and install a default route pointing at a
device with no upstream connectivity.

The symptom is confusing on a dual-stack network, because IPv4 keeps
working while anything preferring IPv6 fails. Users describe it as "some
things work," which sends people looking in the wrong place.

**How to check**

    Identify                                             [active test]
      tcpdump -i <if> -n 'icmp6 && ip6[40] == 134'
        -> read the source link-local address and MAC of each RA
      rafixd or ndpmon, if you run them

    Client                                               [read-only]
      ip -6 route show          is the default route via an unexpected address?
      ip -6 neigh show
      show ipv6 routers                                  on a Cisco host or device

    Trace it                                             [read-only]
      show mac address-table address <rogue-mac>
      -> which switchport? shut it.
    Prevent                                              [change approval]
      RA Guard on access ports (IPv6 first-hop security)
      ipv6 nd raguard policy HOST
      ipv6 nd raguard attach-policy HOST      on user-facing ports
      Combine with DHCPv6 Guard and IPv6 Source Guard

**Watch out for.** RA Guard is the IPv6 equivalent of BPDU Guard, and
most enterprise networks that enabled the IPv4 protections never enabled
the IPv6 ones. Pointing that out unprompted is a strong signal, because
it shows you think about dual-stack parity rather than treating IPv6 as
an afterthought.

**References:** [RFC 6104, Rogue IPv6 RA Problem
Statement](https://www.rfc-editor.org/rfc/rfc6104.html) · [RFC 6105,
IPv6 Router Advertisement
Guard](https://www.rfc-editor.org/rfc/rfc6105.html)

### Q105. Clients get an IPv6 address but no DNS server

*Tier: L2. Safety: read-only.*

**Short answer.** The Router Advertisement's M and O flags decide
whether clients also ask DHCPv6, and for what. If neither flag is set
and the RA carries no RDNSS option, hosts get an address and no
resolver.

**What is actually going on.** IPv6 address configuration has more
combinations than IPv4, and this is where people get lost. Two flags in
the Router Advertisement control it:

  -----------------------------------------------------------------------
  M flag  O flag Client behaviour
  ------- ------ --------------------------------------------------------
  0       0      SLAAC only. Address from the RA prefix. No DHCPv6 at
                 all.

  0       1      SLAAC for the address, DHCPv6 for other information such
                 as DNS.

  1       any    Stateful DHCPv6 for the address and other information.
  -----------------------------------------------------------------------

So a common misconfiguration is enabling SLAAC, leaving both flags
clear, and expecting DNS to arrive from somewhere. It does not.

There are two ways to supply DNS, and support varies by operating
system:

- **RDNSS and DNSSL options inside the RA itself.** Widely supported
  now, and simpler because it avoids DHCPv6 entirely.
- **Stateless DHCPv6**, which requires the O flag set and a DHCPv6
  server reachable, usually via a relay.

A further wrinkle: some platforms have historically not implemented
DHCPv6 at all, so a design relying solely on DHCPv6 leaves those clients
without configuration. Check what is actually on your network before
choosing.

**How to check**

    Router                                               [read-only]
      show ipv6 interface <if>
        look for "Hosts use stateless autoconfig for addresses"
        and whether the M and O flags are advertised
      show run interface <if> | include ipv6 nd

    Capture the RA and read the flags                    [active test]
      tcpdump -i <if> -vvn 'icmp6 && ip6[40] == 134'
        M = managed address configuration
        O = other configuration
        plus any RDNSS option present

    Client                                               [read-only]
      resolvectl status                                  Linux
      Get-DnsClientServerAddress -AddressFamily IPv6     Windows

**Watch out for.** Decide deliberately between RDNSS in the RA and
stateless DHCPv6, and document which one your network uses.
Half-configuring both is how you end up with clients that resolve on one
VLAN and not on another, which is a miserable fault to chase.

**References:** [RFC 4861, Neighbor
Discovery](https://www.rfc-editor.org/rfc/rfc4861.html) · [RFC 8106,
IPv6 RA Options for DNS
Configuration](https://www.rfc-editor.org/rfc/rfc8106.html) · [RFC 8415,
DHCPv6](https://www.rfc-editor.org/rfc/rfc8415.html)

### Q106. IPv6 connections hang on large transfers while small requests work

*Tier: L3. Safety: active test.*

**Short answer.** Almost the same shape as the IPv4 PMTUD black hole,
but worse, because IPv6 routers do not fragment in transit. If ICMPv6
Packet Too Big messages are filtered, the sender never learns and the
transfer stalls permanently.

**What is actually going on.** This is where blocking ICMPv6 stops being
merely unwise and becomes an outage.

In IPv4, a router may fragment an oversized packet if DF is clear. In
IPv6, routers never fragment. Only the source may fragment, and it only
knows to do so if it receives an ICMPv6 Packet Too Big message from the
router that could not forward the packet.

Filter that message and path MTU discovery is dead. Small requests
succeed because they fit. Anything at full size disappears silently and
the sender retransmits it forever.

Tunnels make it more likely, because encapsulation reduces the effective
MTU. The IPv6 minimum link MTU is 1280 bytes, which is why 1280 is the
safe fallback value you will see in tunnel configurations.

Before concluding PMTUD, rule out the same alternatives as in the IPv4
case: proxy or DLP size limits, application timeouts, and server-side
faults. The difference is that in IPv6 the ICMPv6 hypothesis deserves to
be checked first, not last.

**How to check**

                                                        # [active test]
    ping6 -M do -s 1452 <dest>       # 1452 + 48 = 1500 for IPv6
    tracepath6 <dest>                # reports MTU changes along the path

    # Are Packet Too Big messages arriving?
    tcpdump -i <if> -n 'icmp6 && ip6[40] == 2'
    Firewall policy that must exist for IPv6             [change approval]
      permit icmpv6 type 1     destination unreachable
      permit icmpv6 type 2     packet too big          <- essential
      permit icmpv6 type 3     time exceeded
      permit icmpv6 type 4     parameter problem
      permit icmpv6 types 133-137 on-link only  (ND: RS, RA, NS, NA, redirect)

    Interim mitigation
      ipv6 tcp adjust-mss 1220        on the tunnel interface

**Watch out for.** If someone has written an IPv6 firewall policy by
copying the IPv4 one, ICMPv6 is very likely over-filtered. Checking that
is a five-minute job that resolves a class of faults people chase for
days.

**References:** [RFC 8200, IPv6
Specification](https://www.rfc-editor.org/rfc/rfc8200.html) · [RFC 8201,
Path MTU Discovery for
IPv6](https://www.rfc-editor.org/rfc/rfc8201.html) · [RFC 4890,
Filtering ICMPv6 Messages in
Firewalls](https://www.rfc-editor.org/rfc/rfc4890.html)

### Q107. A service you firewalled off is still reachable

*Tier: L3. Safety: read-only.*

**Short answer.** Check whether the IPv6 path is governed by the same
policy as the IPv4 path. Dual-stack networks routinely have complete
IPv4 rules and partial or absent IPv6 rules, so a service blocked on one
protocol stays wide open on the other.

**What is actually going on.** This is one of the most consequential
real-world IPv6 problems and it barely appears in training material.

IPv6 was enabled by default in every mainstream operating system for
years before most organisations wrote IPv6 security policy. The result
is networks where:

- Access lists were written for IPv4 and never duplicated for IPv6
- The firewall has an IPv4 rule base and a much thinner IPv6 one
- Monitoring, logging and NetFlow collection cover IPv4 more completely
- Segmentation is enforced on IPv4 and assumed on IPv6
- Hosts have IPv6 addresses nobody inventoried

An attacker or a curious user reaching the service over IPv6 bypasses
the control entirely. Nothing looks wrong in the IPv4 logs, because
nothing happened there.

**How to check**

    Establish the IPv6 reality                           [read-only]
      show ipv6 interface brief             which interfaces are up on IPv6?
      show ipv6 route
      show ipv6 access-list                 does it exist at all?
      Firewall: compare the IPv4 and IPv6 rule bases side by side

    On the host                                          [read-only]
      ss -ltn                               is the service bound to :: as well?
      netstat -an | findstr "::"            Windows
      ip -6 addr show

                                                         [active test]
      nmap -6 -Pn -p <port> <ipv6-address>  from outside the boundary
    Remediation                                          [change approval]
      - inventory every IPv6-enabled interface and address
      - mirror every IPv4 policy into IPv6, or explicitly document why not
      - if IPv6 is not in use, disable it deliberately at the interface,
        rather than leaving it enabled and unmanaged
      - extend logging, NetFlow and monitoring to IPv6

**Watch out for.** "We don't use IPv6" is almost never true. It is
enabled on the hosts by default and it is doing something. Say it
plainly, then describe how you would verify it rather than assume.

**References:** [RFC 7123, Security Implications of IPv6 on IPv4
Networks](https://www.rfc-editor.org/rfc/rfc7123.html) · [RFC 9099,
Operational Security Considerations for
IPv6](https://www.rfc-editor.org/rfc/rfc9099.html) · [NIST SP 800-119,
Secure IPv6 Deployment](https://csrc.nist.gov/pubs/sp/800/119/final)

### Q108. A hostname returns an AAAA record but the service is unreachable

*Tier: L1. Safety: active test.*

**Short answer.** Something published a AAAA record for a service that
is not actually working over IPv6. Confirm whether the server is
listening on IPv6 and whether the path works, then either fix IPv6
properly or remove the AAAA record until you have.

**What is actually going on.** Publishing a AAAA record is a commitment.
Clients that prefer IPv6 will try that address first, and if it does not
work they wait for a timeout before falling back.

Several things produce a AAAA record without working service:

- The application binds only to an IPv4 socket, so nothing is listening
  on IPv6
- The load balancer has an IPv6 virtual address but IPv4-only backends
  with no translation
- Firewall policy permits the IPv4 address and not the IPv6 one, which
  is Q107 again
- The AAAA record was created during a migration and points at an
  address that no longer exists
- The address is correct but there is no IPv6 route to it from the
  internet

**How to check**

                                                        # [active test]
    dig AAAA service.example.com
    dig A service.example.com

    ping6 <ipv6-address>
    curl -6 -v https://service.example.com/
    nc -6 -vz <ipv6-address> 443
    traceroute6 <ipv6-address>
    On the server                                        [read-only]
      ss -ltn | grep -E ':::|\[::\]'      is it bound to IPv6 at all?
      Get-NetTCPConnection -State Listen  Windows

**Watch out for.** The correct short-term action is often to remove the
AAAA record. It feels like a retreat, but publishing a broken address
degrades every dual-stack client that touches it, and removing it
restores service immediately while you fix IPv6 properly. Say that
clearly, because it separates "the right long-term design" from "the
right thing to do at 2 a.m."

**References:** [RFC 3596, DNS Extensions to Support
IPv6](https://www.rfc-editor.org/rfc/rfc3596.html) · [RFC 8305, Happy
Eyeballs Version 2](https://www.rfc-editor.org/rfc/rfc8305.html)

# Appendix A. Study Paths

The three study paths below sequence the same 108 scenarios by tier. Use
the path for the role you are applying for, then use [Appendix
C](#appendix-c.-self-assessment-tracker) to decide which chapters
deserve extra time. The paths contain 25, 73 and 10 scenarios
respectively.

## A.1 L1 Study Path: NOC Analyst

**25 scenarios** · For your first NOC role, Tier 1 support, or
CCNA-level knowledge

### Who this path is for

You are applying for a first NOC or service desk role, or you have been
in one for a few months and want to stop feeling out of your depth. You
know what a VLAN is and roughly what a router does. You have probably
not troubleshooted a live outage on your own yet.

That is the right starting point. Nobody expects an L1 candidate to
explain BGP best-path selection. What they expect is that you gather the
correct information, do not make things worse, and hand over cleanly
when you reach your limit.

### What interviewers are testing at L1

  -----------------------------------------------------------------------
  They ask                          They are really checking
  --------------------------------- -------------------------------------
  "What would you check first?"     Do you have a method, or do you
                                    guess?

  "What command would you run?"     Have you actually used a CLI?

  "When would you escalate?"        Will you sit on a P1 for two hours
                                    out of pride?

  "How would you explain this to    Can you talk to people who are not
  the user?"                        engineers?
  -----------------------------------------------------------------------

Notice that only half of those are technical. At L1 the process
questions carry as much weight as the protocol questions, which is why
this path includes all of them.

### How to work through this

**Week 1.** Scenarios 1 to 8 below. These are the reachability and
physical layer basics that come up in almost every L1 interview.

**Week 2.** Scenarios 9 to 16. Name resolution, addressing, and the
wireless fundamentals.

**Week 3.** Scenarios 17 to 25. Process, escalation and communication.
Do not skip these. They are the ones candidates underprepare and
interviewers weight heavily.

**Throughout.** For each scenario, cover the answer and say yours out
loud first. Reading and nodding is not studying.

### Before you interview

Build at least three of these in a lab and break them deliberately.
[Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer) is
free and enough for most of this path. Being able to say "I built this
and watched it fail" changes how you answer, and interviewers hear the
difference.

### The scenarios

  ---------------------------------------------------------------------------------------------------------------------------
  \#     Scenario                                                                                           Chapter
  ------ -------------------------------------------------------------------------------------------------- -----------------
  Q1     [A user can't reach a server in another VLAN, but can reach one in the same                        Routing and
         VLAN](#q1.-a-user-cant-reach-a-server-in-another-vlan-but-can-reach-one-in-the-same-vlan)          Switching

  Q6     [A newly added VLAN isn't passing traffic across a trunk                                           Routing and
         link](#q6.-a-newly-added-vlan-isnt-passing-traffic-across-a-trunk-link)                            Switching

  Q7     [Users on one floor lose connectivity randomly, correlating with cleaning staff                    Routing and
         hours](#q7.-users-on-one-floor-lose-connectivity-randomly-correlating-with-cleaning-staff-hours)   Switching

  Q9     [A static route works for one subnet but not its neighbour                                         Routing and
         subnet](#q9.-a-static-route-works-for-one-subnet-but-not-its-neighbour-subnet)                     Switching

  Q10    [Interface counters show high input errors and CRC                                                 Routing and
         errors](#q10.-interface-counters-show-high-input-errors-and-crc-errors)                            Switching

  Q15    [Users can reach IPs directly but not by                                                           DNS and DHCP
         hostname](#q15.-users-can-reach-ips-directly-but-not-by-hostname)                                  

  Q17    [A new laptop can't get an IP address on the                                                       DNS and DHCP
         network](#q17.-a-new-laptop-cant-get-an-ip-address-on-the-network)                                 

  Q20    [Devices are getting APIPA (169.254.x.x)                                                           DNS and DHCP
         addresses](#q20.-devices-are-getting-apipa-169.254.x.x-addresses)                                  

  Q22    [After a DNS record change, some users still resolve the old                                       DNS and DHCP
         IP](#q22.-after-a-dns-record-change-some-users-still-resolve-the-old-ip)                           

  Q38    [A user can VPN in from home but not from a hotel                                                  VPN and Remote
         Wi-Fi](#q38.-a-user-can-vpn-in-from-home-but-not-from-a-hotel-wi-fi)                               Access

  Q44    [Wireless throughput is much lower than wired for the same                                         Wireless
         user](#q44.-wireless-throughput-is-much-lower-than-wired-for-the-same-user)                        

  Q48    [Users near the kitchen experience 2.4 GHz Wi-Fi                                                   Wireless
         dropouts](#q48.-users-near-the-kitchen-experience-2.4-ghz-wi-fi-dropouts)                          

  Q50    [Monitoring floods with hundreds of alerts during a single                                         Monitoring and
         outage](#q50.-monitoring-floods-with-hundreds-of-alerts-during-a-single-outage)                    NOC Process

  Q53    [Ticket volume for the same issue is coming in from multiple                                       Monitoring and
         sites](#q53.-ticket-volume-for-the-same-issue-is-coming-in-from-multiple-sites)                    NOC Process

  Q54    [Monitoring shows 100% packet loss to a device users say is working                                Monitoring and
         fine](#q54.-monitoring-shows-100-packet-loss-to-a-device-users-say-is-working-fine)                NOC Process

  Q55    [How do you decide whether to escalate or keep                                                     Monitoring and
         troubleshooting?](#q55.-how-do-you-decide-whether-to-escalate-or-keep-troubleshooting)             NOC Process

  Q56    [A maintenance window causes unexpected alerts to page on-call                                     Monitoring and
         staff](#q56.-a-maintenance-window-causes-unexpected-alerts-to-page-on-call-staff)                  NOC Process

  Q57    [How do you document a resolved incident for future                                                Monitoring and
         reference?](#q57.-how-do-you-document-a-resolved-incident-for-future-reference)                    NOC Process

  Q79    [A newly terminated cable passes a link light but has a high error                                 Physical Layer
         rate](#q79.-a-newly-terminated-cable-passes-a-link-light-but-has-a-high-error-rate)                

  Q80    [A fibre link shows light-loss readings well beyond                                                Physical Layer
         spec](#q80.-a-fibre-link-shows-light-loss-readings-well-beyond-spec)                               

  Q81    [A patch panel port works but the same run at the wall jack                                        Physical Layer
         doesn't](#q81.-a-patch-panel-port-works-but-the-same-run-at-the-wall-jack-doesnt)                  

  Q82    [A copper run works at 100 Mbps but fails at                                                       Physical Layer
         gigabit](#q82.-a-copper-run-works-at-100-mbps-but-fails-at-gigabit)                                

  Q91    [How do you stay aware of network changes across                                                   Escalation and
         departments?](#q91.-how-do-you-stay-aware-of-network-changes-across-departments)                   ITIL

  Q103   [Clients have an IPv6 address but no IPv6                                                          IPv6
         connectivity](#q103.-clients-have-an-ipv6-address-but-no-ipv6-connectivity)                        

  Q108   [A hostname returns an AAAA record but the service is                                              IPv6
         unreachable](#q108.-a-hostname-returns-an-aaaa-record-but-the-service-is-unreachable)              
  ---------------------------------------------------------------------------------------------------------------------------

### What to say when you do not know

You will be asked something outside this path. That is deliberate;
interviewers want to see how you behave at the edge of your knowledge.

The answer that works: say what you do know, say plainly what you do
not, and describe how you would find out. "I have not worked with that
directly. I know it sits at Layer 3 and I would start by checking the
routing table and the interface state, then look at the vendor
documentation or escalate to Tier 2 if I was not making progress."

The answer that fails: guessing confidently. Every experienced engineer
can tell, and it makes them wonder what else you have guessed at.

## A.2 L2 Study Path: NOC Engineer

**73 scenarios** · For Tier 2, shift engineer, or 2 to 5 years of
experience

### Who this path is for

You already work in a NOC. You recognise most of these symptoms and you
have fixed several of them. What you may not have done is explain *why*
they happen to someone who is deliberately probing for gaps.

This is the largest path by a wide margin, and that is not an accident.
Most NOC hiring happens at L2, and it is where the majority of
candidates get caught out.

### What interviewers are testing at L2

The single biggest difference from L1 is the follow-up question. At L1
you are asked what you would check. At L2 you are asked what you would
check, and then you are asked **why**. Sometimes twice.

  ---------------------------------------------------------------------------
  Level   Question                    Adequate answer
  ------- --------------------------- ---------------------------------------
  L1      "OSPF neighbours will not   Timers, area ID, MTU, authentication
          form. What do you check?"   

  L2      "It is stuck in ExStart.    MTU mismatch, because DD packets carry
          What does that tell you?"   MTU and are rejected when it differs
  ---------------------------------------------------------------------------

If you can only produce the first answer, you interview as an L1
candidate regardless of your job title. The *What is actually going on*
section of each scenario is where that gap gets closed, so read those
properly rather than skimming to the commands.

### How to work through this

Do not work through it in order. 73 scenarios read front to back will
blur together and you will retain little.

Instead:

1.  **Diagnose yourself first.** Use the [self-assessment
    tracker](#appendix-c.-self-assessment-tracker) and score each
    chapter honestly. Anything below 3 is where your time belongs.
2.  **Work by domain, not by tier.** Read the whole DNS chapter, then
    the whole VPN chapter. Related scenarios reinforce each other, and
    that is exactly why this guide is organised by topic rather than by
    tier.
3.  **Use the [questions-only
    edition](#appendix-b.-questions-only-recall-edition)** for recall
    practice once you have read a chapter.
4.  **Lab the ones you have never seen in production.** You will be
    asked "have you dealt with this yourself?" and a lab is an honest
    answer.

### The mechanisms most worth memorising

If you are short on time, these are the explanations that come up most
often and differentiate most sharply:

- **OSPF adjacency states map to specific causes.** Stuck in ExStart
  means MTU.
- **PMTUD black holes** happen when ICMP is filtered, and they are why
  downloads hang over tunnels.
- **Stateful versus stateless** is why cloud NACLs need explicit return
  rules and security groups do not.
- **Encaps rising, decaps flat** on an IPsec SA tells you which end owns
  the problem.
- **Precise repeating intervals** mean a timer. Random failures mean
  congestion or loss.
- **Health check depth** is why a load balancer keeps feeding a dead
  server.
- **Wireless is half duplex and shared**, which is why airtime, not
  signal strength, explains most performance complaints.

### The scenarios

  ---------------------------------------------------------------------------------------------------------------------------------
  \#     Scenario                                                                                                Chapter
  ------ ------------------------------------------------------------------------------------------------------- ------------------
  Q2     [Two switches show a spanning-tree topology change every few                                            Routing and
         minutes](#q2.-two-switches-show-a-spanning-tree-topology-change-every-few-minutes)                      Switching

  Q3     [After adding a new switch, users report intermittent broadcast                                         Routing and
         storms](#q3.-after-adding-a-new-switch-users-report-intermittent-broadcast-storms)                      Switching

  Q4     [A route works via traceroute but pings drop 50% of the                                                 Routing and
         time](#q4.-a-route-works-via-traceroute-but-pings-drop-50-of-the-time)                                  Switching

  Q5     [OSPF neighbors won't form between two routers on the same                                              Routing and
         subnet](#q5.-ospf-neighbors-wont-form-between-two-routers-on-the-same-subnet)                           Switching

  Q8     [Router CPU spikes to 99% during peak hours](#q8.-router-cpu-spikes-to-99-during-peak-hours)            Routing and
                                                                                                                 Switching

  Q11    [Users behind an EtherChannel report slow throughput despite it showing                                 Routing and
         "up"](#q11.-users-behind-an-etherchannel-report-slow-throughput-despite-it-showing-up)                  Switching

  Q12    [A default route was removed accidentally and internet access failed                                    Routing and
         network-wide](#q12.-a-default-route-was-removed-accidentally-and-internet-access-failed-network-wide)   Switching

  Q16    [Internal DNS resolves fine but external domains fail                                                   DNS and DHCP
         intermittently](#q16.-internal-dns-resolves-fine-but-external-domains-fail-intermittently)              

  Q18    [A branch office DHCP scope is exhausted despite low                                                    DNS and DHCP
         headcount](#q18.-a-branch-office-dhcp-scope-is-exhausted-despite-low-headcount)                         

  Q19    [A DNS server is up, but one specific domain always times                                               DNS and DHCP
         out](#q19.-a-dns-server-is-up-but-one-specific-domain-always-times-out)                                 

  Q21    [A dual-homed server intermittently registers the wrong IP in                                           DNS and DHCP
         DNS](#q21.-a-dual-homed-server-intermittently-registers-the-wrong-ip-in-dns)                            

  Q23    [Traffic is allowed by an ACL but still blocked](#q23.-traffic-is-allowed-by-an-acl-but-still-blocked)  Firewall and
                                                                                                                 Security

  Q24    [After a firewall rule update, VoIP calls drop after about 30                                           Firewall and
         seconds](#q24.-after-a-firewall-rule-update-voip-calls-drop-after-about-30-seconds)                     Security

  Q25    [Users can't access a site that used to work, now blocked by URL                                        Firewall and
         filtering](#q25.-users-cant-access-a-site-that-used-to-work-now-blocked-by-url-filtering)               Security

  Q26    [A perimeter firewall shows a spike in denied connections from one external                             Firewall and
         IP](#q26.-a-perimeter-firewall-shows-a-spike-in-denied-connections-from-one-external-ip)                Security

  Q27    [A site-to-site tunnel is up but no traffic                                                             Firewall and
         passes](#q27.-a-site-to-site-tunnel-is-up-but-no-traffic-passes)                                        Security

  Q28    [An internal server suddenly can't be reached from outside after a                                      Firewall and
         change](#q28.-an-internal-server-suddenly-cant-be-reached-from-outside-after-a-change)                  Security

  Q29    [A user's laptop is quarantined by NAC without                                                          Firewall and
         explanation](#q29.-a-users-laptop-is-quarantined-by-nac-without-explanation)                            Security

  Q30    [Repeated login failures from many source IPs against one admin                                         Firewall and
         account](#q30.-repeated-login-failures-from-many-source-ips-against-one-admin-account)                  Security

  Q32    [A misconfigured ACL blocked a critical application at 2                                                Firewall and
         AM](#q32.-a-misconfigured-acl-blocked-a-critical-application-at-2-am)                                   Security

  Q35    [A remote worker connects to VPN but can't access internal file                                         VPN and Remote
         shares](#q35.-a-remote-worker-connects-to-vpn-but-cant-access-internal-file-shares)                     Access

  Q36    [A VPN client repeatedly disconnects at about the same                                                  VPN and Remote
         interval](#q36.-a-vpn-client-repeatedly-disconnects-at-about-the-same-interval)                         Access

  Q37    [A site-to-site VPN drops whenever large file transfers                                                 VPN and Remote
         start](#q37.-a-site-to-site-vpn-drops-whenever-large-file-transfers-start)                              Access

  Q39    [After a VPN concentrator upgrade, users get "certificate not trusted"                                  VPN and Remote
         errors](#q39.-after-a-vpn-concentrator-upgrade-users-get-certificate-not-trusted-errors)                Access

  Q40    [Split-tunnel VPN users report both slow internet and slow internal                                     VPN and Remote
         resources](#q40.-split-tunnel-vpn-users-report-both-slow-internet-and-slow-internal-resources)          Access

  Q41    [A remote office has poor VPN performance despite a good local speed                                    VPN and Remote
         test](#q41.-a-remote-office-has-poor-vpn-performance-despite-a-good-local-speed-test)                   Access

  Q42    [Users experience random Wi-Fi disconnects only in one area of the                                      Wireless
         building](#q42.-users-experience-random-wi-fi-disconnects-only-in-one-area-of-the-building)             

  Q43    [A new AP was added but clients still connect to a farther, weaker                                      Wireless
         AP](#q43.-a-new-ap-was-added-but-clients-still-connect-to-a-farther-weaker-ap)                          

  Q45    [Guest Wi-Fi users can access internal VLANs                                                            Wireless
         unexpectedly](#q45.-guest-wi-fi-users-can-access-internal-vlans-unexpectedly)                           

  Q46    [Certain IoT devices fail to connect to a WPA2-Enterprise                                               Wireless
         SSID](#q46.-certain-iot-devices-fail-to-connect-to-a-wpa2-enterprise-ssid)                              

  Q47    [After a wireless controller firmware update, multiple APs go                                           Wireless
         offline](#q47.-after-a-wireless-controller-firmware-update-multiple-aps-go-offline)                     

  Q49    [Wi-Fi calling quality is choppy while data works                                                       Wireless
         fine](#q49.-wi-fi-calling-quality-is-choppy-while-data-works-fine)                                      

  Q51    [A critical alert didn't page anyone during last night's                                                Monitoring and NOC
         outage](#q51.-a-critical-alert-didnt-page-anyone-during-last-nights-outage)                             Process

  Q52    [A flapping "interface down/up" alert every 5 minutes on a core                                         Monitoring and NOC
         switch](#q52.-a-flapping-interface-downup-alert-every-5-minutes-on-a-core-switch)                       Process

  Q58    [Bandwidth graphs show a steady climb toward saturation on a WAN                                        Monitoring and NOC
         link](#q58.-bandwidth-graphs-show-a-steady-climb-toward-saturation-on-a-wan-link)                       Process

  Q59    [A P1 ticket sits untouched for 20 minutes because the engineer is on                                   Monitoring and NOC
         break](#q59.-a-p1-ticket-sits-untouched-for-20-minutes-because-the-engineer-is-on-break)                Process

  Q60    [Multiple monitoring tools report the same outage at different                                          Monitoring and NOC
         severities](#q60.-multiple-monitoring-tools-report-the-same-outage-at-different-severities)             Process

  Q61    [You've fixed an issue but the dashboard still shows                                                    Monitoring and NOC
         red](#q61.-youve-fixed-an-issue-but-the-dashboard-still-shows-red)                                      Process

  Q62    [Another team's change caused an outage and the NOC wasn't                                              Monitoring and NOC
         told](#q62.-another-teams-change-caused-an-outage-and-the-noc-wasnt-told)                               Process

  Q63    [Your shift is ending but an incident isn't                                                             Monitoring and NOC
         resolved](#q63.-your-shift-is-ending-but-an-incident-isnt-resolved)                                     Process

  Q64    [Configuration drift is causing repeat incidents across similar                                         Monitoring and NOC
         devices](#q64.-configuration-drift-is-causing-repeat-incidents-across-similar-devices)                  Process

  Q65    [A load balancer keeps sending traffic to a backend server that's                                       Cloud and Load
         down](#q65.-a-load-balancer-keeps-sending-traffic-to-a-backend-server-thats-down)                       Balancing

  Q66    [Users experience session drops with a round-robin load                                                 Cloud and Load
         balancer](#q66.-users-experience-session-drops-with-a-round-robin-load-balancer)                        Balancing

  Q67    [Cloud instances can't reach the internet despite having a public                                       Cloud and Load
         IP](#q67.-cloud-instances-cant-reach-the-internet-despite-having-a-public-ip)                           Balancing

  Q69    [An app in the cloud is reachable internally but not from on-prem over                                  Cloud and Load
         VPN](#q69.-an-app-in-the-cloud-is-reachable-internally-but-not-from-on-prem-over-vpn)                   Balancing

  Q70    [Auto-scaling added instances but the load balancer isn't sending them                                  Cloud and Load
         traffic](#q70.-auto-scaling-added-instances-but-the-load-balancer-isnt-sending-them-traffic)            Balancing

  Q71    [Cross-region cloud traffic has unexpectedly high                                                       Cloud and Load
         latency](#q71.-cross-region-cloud-traffic-has-unexpectedly-high-latency)                                Balancing

  Q73    [Calls are fine most of the day but become choppy around 5                                              VoIP and QoS
         PM](#q73.-calls-are-fine-most-of-the-day-but-become-choppy-around-5-pm)                                 

  Q74    [One-way audio is reported on calls between two                                                         VoIP and QoS
         sites](#q74.-one-way-audio-is-reported-on-calls-between-two-sites)                                      

  Q75    [VoIP quality complaints only come from wireless users, not wired                                       VoIP and QoS
         ones](#q75.-voip-quality-complaints-only-come-from-wireless-users-not-wired-ones)                       

  Q76    [Softphone calls drop at a precise repeating                                                            VoIP and QoS
         interval](#q76.-softphone-calls-drop-at-a-precise-repeating-interval)                                   

  Q77    [After a WAN bandwidth upgrade, voice quality got                                                       VoIP and QoS
         worse](#q77.-after-a-wan-bandwidth-upgrade-voice-quality-got-worse)                                     

  Q78    [Conference calls degrade only above about 10                                                           VoIP and QoS
         participants](#q78.-conference-calls-degrade-only-above-about-10-participants)                          

  Q83    [An SFP transceiver shows link down despite being properly                                              Physical Layer
         seated](#q83.-an-sfp-transceiver-shows-link-down-despite-being-properly-seated)                         

  Q84    [Multiple ports on the same switch card show errors after a power                                       Physical Layer
         event](#q84.-multiple-ports-on-the-same-switch-card-show-errors-after-a-power-event)                    

  Q85    [A vendor's ticket for a circuit outage isn't                                                           Escalation and
         progressing](#q85.-a-vendors-ticket-for-a-circuit-outage-isnt-progressing)                              ITIL

  Q86    [You suspect another team's change caused an issue but they deny                                        Escalation and
         it](#q86.-you-suspect-another-teams-change-caused-an-issue-but-they-deny-it)                            ITIL

  Q87    [How do you triage several simultaneous incidents with limited                                          Escalation and
         staff?](#q87.-how-do-you-triage-several-simultaneous-incidents-with-limited-staff)                      ITIL

  Q88    [A recurring issue keeps getting temporary                                                              Escalation and
         fixes](#q88.-a-recurring-issue-keeps-getting-temporary-fixes)                                           ITIL

  Q89    [How do you communicate with stakeholders during a major                                                Escalation and
         outage?](#q89.-how-do-you-communicate-with-stakeholders-during-a-major-outage)                          ITIL

  Q90    [A change you made caused unexpected downtime. What's your next                                         Escalation and
         step?](#q90.-a-change-you-made-caused-unexpected-downtime.-whats-your-next-step)                        ITIL

  Q92    [A Linux server can ping its gateway but not any other                                                  Server and OS
         host](#q92.-a-linux-server-can-ping-its-gateway-but-not-any-other-host)                                 Networking

  Q93    [A Windows server loses connectivity right after an                                                     Server and OS
         update](#q93.-a-windows-server-loses-connectivity-right-after-an-update)                                Networking

  Q94    [Two NICs on a server in the same subnet cause intermittent                                             Server and OS
         connectivity](#q94.-two-nics-on-a-server-in-the-same-subnet-cause-intermittent-connectivity)            Networking

  Q95    [A server's throughput is capped well below the NIC's rated                                             Server and OS
         speed](#q95.-a-servers-throughput-is-capped-well-below-the-nics-rated-speed)                            Networking

  Q96    [A hostname resolves fine but TLS certificate errors happen                                             Server and OS
         intermittently](#q96.-a-hostname-resolves-fine-but-tls-certificate-errors-happen-intermittently)        Networking

  Q97    [Users complain email is delayed by up to an hour but eventually                                        Miscellaneous
         delivers](#q97.-users-complain-email-is-delayed-by-up-to-an-hour-but-eventually-delivers)               Protocols

  Q98    [FTP fails in passive mode through the firewall but works in active                                     Miscellaneous
         mode](#q98.-ftp-fails-in-passive-mode-through-the-firewall-but-works-in-active-mode)                    Protocols

  Q99    [NTP sync failures are causing certificate and authentication                                           Miscellaneous
         errors](#q99.-ntp-sync-failures-are-causing-certificate-and-authentication-errors)                      Protocols

  Q100   [SNMP polling fails for a subset of devices after a hardening                                           Miscellaneous
         project](#q100.-snmp-polling-fails-for-a-subset-of-devices-after-a-hardening-project)                   Protocols

  Q102   [A website is slow to load for some users but fine for others on the same                               IPv6
         network](#q102.-a-website-is-slow-to-load-for-some-users-but-fine-for-others-on-the-same-network)       

  Q104   [Users on one VLAN suddenly lose connectivity after someone plugs in a home                             IPv6
         router](#q104.-users-on-one-vlan-suddenly-lose-connectivity-after-someone-plugs-in-a-home-router)       

  Q105   [Clients get an IPv6 address but no DNS server](#q105.-clients-get-an-ipv6-address-but-no-dns-server)   IPv6
  ---------------------------------------------------------------------------------------------------------------------------------

### The question behind the question

At L2, interviewers are also assessing whether you can be left alone on
a night shift. Several scenarios in this path are really about that:
escalation timing, handover quality, and whether you check the change
calendar before theorising.

Answer those with the same seriousness as the protocol questions. A
candidate who is technically strong and operationally careless is a
risk, and experienced interviewers screen for it deliberately.

## A.3 L3 Study Path: Senior and Escalation Engineer

**10 scenarios** · For senior NOC, escalation engineer, or network
specialist roles

### Who this path is for

You are the person the L2 team escalates to. You are expected to reason
about protocol behaviour from first principles, work from packet-level
evidence, and design failures out rather than fix them repeatedly.

### Why this path is short

Ten scenarios, against seventy-three at L2. That is deliberate and worth
explaining, because the imbalance is a real property of the material
rather than an oversight.

Senior interviews test differently. They rarely ask "what causes X."
They ask you to reason out loud about something ambiguous, then push on
your reasoning to see whether it holds. The value is in depth per
scenario, not coverage.

They also test judgement more than recall: when *not* to roll back, when
a datasheet number was the real problem, when to tell a stakeholder you
have no reliable ETA. Several of those live in the [Escalation
chapter](#chapter-10.-escalation-itil-and-communication) and are marked
L2 there, but they are asked at senior interviews with harder
follow-ups.

**So treat this path as a supplement, not a substitute.** Work the full
L2 path as well. What changes at L3 is the depth you are expected to
reach on any of it, not the topics.

### What interviewers are testing at L3

  -----------------------------------------------------------------------
  They ask                          They are really checking
  --------------------------------- -------------------------------------
  "Walk me through how you would    Can you reason without knowing the
  approach this."                   answer in advance?

  "Why does that happen?"           Do you understand the protocol, or
  repeatedly                        the symptom?

  "What would you do if rollback    Do you have judgement, or a memorised
  was not available?"               procedure?

  "How would you stop this          Do you think in systems or in
  recurring?"                       tickets?

  "What is your evidence?"          Do you reason from data or from
                                    assumption?
  -----------------------------------------------------------------------

The last one matters most. A senior candidate who says "it is probably
MTU" has given a worse answer than one who says "the symptom fits PMTUD,
and I would confirm with a DF-bit sweep before committing, because a
proxy file size limit produces the same complaint."

### How to work through this

Read each scenario, then argue with it. Every one of these has at least
one alternative explanation the answer does not fully cover. Find it.
That is the exercise.

Then explain the mechanism out loud to someone who is not a network
engineer. If you cannot, you do not understand it well enough to defend
it under a third follow-up question.

### The scenarios

  ------------------------------------------------------------------------------------------------------------------------------------
  \#     Scenario                                                                                                     Chapter
  ------ ------------------------------------------------------------------------------------------------------------ ----------------
  Q13    [A BGP peer is up, but a prefix you expect is                                                                Routing and
         missing](#q13.-a-bgp-peer-is-up-but-a-prefix-you-expect-is-missing)                                          Switching

  Q14    [A gateway failover didn't happen when the primary router                                                    Routing and
         failed](#q14.-a-gateway-failover-didnt-happen-when-the-primary-router-failed)                                Switching

  Q31    [After enabling deep packet inspection, throughput                                                           Firewall and
         drops](#q31.-after-enabling-deep-packet-inspection-throughput-drops)                                         Security

  Q33    [Users can browse sites but file downloads consistently fail or                                              Firewall and
         hang](#q33.-users-can-browse-sites-but-file-downloads-consistently-fail-or-hang)                             Security

  Q34    [Remote sites behind different firewall vendors report inconsistent VPN                                      Firewall and
         compatibility](#q34.-remote-sites-behind-different-firewall-vendors-report-inconsistent-vpn-compatibility)   Security

  Q68    [A hybrid cloud connection shows intermittent BGP                                                            Cloud and Load
         flaps](#q68.-a-hybrid-cloud-connection-shows-intermittent-bgp-flaps)                                         Balancing

  Q72    [A security group update blocked traffic that used to work through the NAT                                   Cloud and Load
         gateway](#q72.-a-security-group-update-blocked-traffic-that-used-to-work-through-the-nat-gateway)            Balancing

  Q101   [One particular TCP port randomly fails while others                                                         Miscellaneous
         work](#q101.-one-particular-tcp-port-randomly-fails-while-others-work)                                       Protocols

  Q106   [IPv6 connections hang on large transfers while small requests                                               IPv6
         work](#q106.-ipv6-connections-hang-on-large-transfers-while-small-requests-work)                             

  Q107   [A service you firewalled off is still reachable](#q107.-a-service-you-firewalled-off-is-still-reachable)    IPv6
  ------------------------------------------------------------------------------------------------------------------------------------

### A note on how these were written

Several scenarios in this guide were corrected after a technical audit
found overconfident or incorrect explanations, and this edition adds
further corrections. The corrections made for this edition are listed in
[Appendix I](#appendix_i).

That is relevant to you specifically. At L3 you will be interviewing
people, reviewing designs and signing off changes, and the most useful
habit in this guide is not any single mechanism. It is the practice of
separating "the evidence supports this" from "this is the explanation I
reached for first."

If you find something here that is still wrong, report it using the
address in [Publication Details](#feedback). Corrections are genuinely
welcome.

# Appendix B. Questions-Only Recall Edition

**All 108 scenarios with no answers visible.** Use this for active
recall.

## How to use this properly

Read the question. Say your answer **out loud**, in full sentences, as
if an interviewer is sitting opposite you. Only then follow the link to
check.

That last part matters more than it sounds. Reading a question, thinking
"yes, I know that one," and moving on is recognition, not recall.
Recognition feels like knowledge right up until someone is watching you
and you have to produce the words.

Three rules that make this work:

1.  **Speak, do not think.** The gap between knowing something and being
    able to say it under pressure is exactly what interviews expose.
2.  **Give the mechanism, not just the cause.** After your answer, ask
    yourself "why does that happen?" If you cannot answer that, mark the
    scenario.
3.  **Time yourself.** Aim for 60 to 90 seconds per answer. Interview
    answers that run past two minutes lose the room.

Mark anything you could not answer cleanly and take it to the
[self-assessment tracker](#appendix-c.-self-assessment-tracker).

## Chapter 1. Routing and Switching

**Q1.** A user can't reach a server in another VLAN, but can reach one
in the same VLAN\
`L1` ·
[answer](#q1.-a-user-cant-reach-a-server-in-another-vlan-but-can-reach-one-in-the-same-vlan)

**Q2.** Two switches show a spanning-tree topology change every few
minutes\
`L2` ·
[answer](#q2.-two-switches-show-a-spanning-tree-topology-change-every-few-minutes)

**Q3.** After adding a new switch, users report intermittent broadcast
storms\
`L2` ·
[answer](#q3.-after-adding-a-new-switch-users-report-intermittent-broadcast-storms)

**Q4.** A route works via traceroute but pings drop 50% of the time\
`L2` ·
[answer](#q4.-a-route-works-via-traceroute-but-pings-drop-50-of-the-time)

**Q5.** OSPF neighbors won't form between two routers on the same
subnet\
`L2` ·
[answer](#q5.-ospf-neighbors-wont-form-between-two-routers-on-the-same-subnet)

**Q6.** A newly added VLAN isn't passing traffic across a trunk link\
`L1` ·
[answer](#q6.-a-newly-added-vlan-isnt-passing-traffic-across-a-trunk-link)

**Q7.** Users on one floor lose connectivity randomly, correlating with
cleaning staff hours\
`L1` ·
[answer](#q7.-users-on-one-floor-lose-connectivity-randomly-correlating-with-cleaning-staff-hours)

**Q8.** Router CPU spikes to 99% during peak hours\
`L2` · [answer](#q8.-router-cpu-spikes-to-99-during-peak-hours)

**Q9.** A static route works for one subnet but not its neighbour
subnet\
`L1` ·
[answer](#q9.-a-static-route-works-for-one-subnet-but-not-its-neighbour-subnet)

**Q10.** Interface counters show high input errors and CRC errors\
`L1` ·
[answer](#q10.-interface-counters-show-high-input-errors-and-crc-errors)

**Q11.** Users behind an EtherChannel report slow throughput despite it
showing "up"\
`L2` ·
[answer](#q11.-users-behind-an-etherchannel-report-slow-throughput-despite-it-showing-up)

**Q12.** A default route was removed accidentally and internet access
failed network-wide\
`L2` ·
[answer](#q12.-a-default-route-was-removed-accidentally-and-internet-access-failed-network-wide)

**Q13.** A BGP peer is up, but a prefix you expect is missing\
`L3` ·
[answer](#q13.-a-bgp-peer-is-up-but-a-prefix-you-expect-is-missing)

**Q14.** A gateway failover didn't happen when the primary router
failed\
`L3` ·
[answer](#q14.-a-gateway-failover-didnt-happen-when-the-primary-router-failed)

## Chapter 2. DNS and DHCP

**Q15.** Users can reach IPs directly but not by hostname\
`L1` · [answer](#q15.-users-can-reach-ips-directly-but-not-by-hostname)

**Q16.** Internal DNS resolves fine but external domains fail
intermittently\
`L2` ·
[answer](#q16.-internal-dns-resolves-fine-but-external-domains-fail-intermittently)

**Q17.** A new laptop can't get an IP address on the network\
`L1` ·
[answer](#q17.-a-new-laptop-cant-get-an-ip-address-on-the-network)

**Q18.** A branch office DHCP scope is exhausted despite low headcount\
`L2` ·
[answer](#q18.-a-branch-office-dhcp-scope-is-exhausted-despite-low-headcount)

**Q19.** A DNS server is up, but one specific domain always times out\
`L2` ·
[answer](#q19.-a-dns-server-is-up-but-one-specific-domain-always-times-out)

**Q20.** Devices are getting APIPA (169.254.x.x) addresses\
`L1` · [answer](#q20.-devices-are-getting-apipa-169.254.x.x-addresses)

**Q21.** A dual-homed server intermittently registers the wrong IP in
DNS\
`L2` ·
[answer](#q21.-a-dual-homed-server-intermittently-registers-the-wrong-ip-in-dns)

**Q22.** After a DNS record change, some users still resolve the old IP\
`L1` ·
[answer](#q22.-after-a-dns-record-change-some-users-still-resolve-the-old-ip)

## Chapter 3. Firewall and Security

**Q23.** Traffic is allowed by an ACL but still blocked\
`L2` · [answer](#q23.-traffic-is-allowed-by-an-acl-but-still-blocked)

**Q24.** After a firewall rule update, VoIP calls drop after about 30
seconds\
`L2` ·
[answer](#q24.-after-a-firewall-rule-update-voip-calls-drop-after-about-30-seconds)

**Q25.** Users can't access a site that used to work, now blocked by URL
filtering\
`L2` ·
[answer](#q25.-users-cant-access-a-site-that-used-to-work-now-blocked-by-url-filtering)

**Q26.** A perimeter firewall shows a spike in denied connections from
one external IP\
`L2` ·
[answer](#q26.-a-perimeter-firewall-shows-a-spike-in-denied-connections-from-one-external-ip)

**Q27.** A site-to-site tunnel is up but no traffic passes\
`L2` · [answer](#q27.-a-site-to-site-tunnel-is-up-but-no-traffic-passes)

**Q28.** An internal server suddenly can't be reached from outside after
a change\
`L2` ·
[answer](#q28.-an-internal-server-suddenly-cant-be-reached-from-outside-after-a-change)

**Q29.** A user's laptop is quarantined by NAC without explanation\
`L2` ·
[answer](#q29.-a-users-laptop-is-quarantined-by-nac-without-explanation)

**Q30.** Repeated login failures from many source IPs against one admin
account\
`L2` ·
[answer](#q30.-repeated-login-failures-from-many-source-ips-against-one-admin-account)

**Q31.** After enabling deep packet inspection, throughput drops\
`L3` ·
[answer](#q31.-after-enabling-deep-packet-inspection-throughput-drops)

**Q32.** A misconfigured ACL blocked a critical application at 2 AM\
`L2` ·
[answer](#q32.-a-misconfigured-acl-blocked-a-critical-application-at-2-am)

**Q33.** Users can browse sites but file downloads consistently fail or
hang\
`L3` ·
[answer](#q33.-users-can-browse-sites-but-file-downloads-consistently-fail-or-hang)

**Q34.** Remote sites behind different firewall vendors report
inconsistent VPN compatibility\
`L3` ·
[answer](#q34.-remote-sites-behind-different-firewall-vendors-report-inconsistent-vpn-compatibility)

## Chapter 4. VPN and Remote Access

**Q35.** A remote worker connects to VPN but can't access internal file
shares\
`L2` ·
[answer](#q35.-a-remote-worker-connects-to-vpn-but-cant-access-internal-file-shares)

**Q36.** A VPN client repeatedly disconnects at about the same interval\
`L2` ·
[answer](#q36.-a-vpn-client-repeatedly-disconnects-at-about-the-same-interval)

**Q37.** A site-to-site VPN drops whenever large file transfers start\
`L2` ·
[answer](#q37.-a-site-to-site-vpn-drops-whenever-large-file-transfers-start)

**Q38.** A user can VPN in from home but not from a hotel Wi-Fi\
`L1` ·
[answer](#q38.-a-user-can-vpn-in-from-home-but-not-from-a-hotel-wi-fi)

**Q39.** After a VPN concentrator upgrade, users get "certificate not
trusted" errors\
`L2` ·
[answer](#q39.-after-a-vpn-concentrator-upgrade-users-get-certificate-not-trusted-errors)

**Q40.** Split-tunnel VPN users report both slow internet and slow
internal resources\
`L2` ·
[answer](#q40.-split-tunnel-vpn-users-report-both-slow-internet-and-slow-internal-resources)

**Q41.** A remote office has poor VPN performance despite a good local
speed test\
`L2` ·
[answer](#q41.-a-remote-office-has-poor-vpn-performance-despite-a-good-local-speed-test)

## Chapter 5. Wireless

**Q42.** Users experience random Wi-Fi disconnects only in one area of
the building\
`L2` ·
[answer](#q42.-users-experience-random-wi-fi-disconnects-only-in-one-area-of-the-building)

**Q43.** A new AP was added but clients still connect to a farther,
weaker AP\
`L2` ·
[answer](#q43.-a-new-ap-was-added-but-clients-still-connect-to-a-farther-weaker-ap)

**Q44.** Wireless throughput is much lower than wired for the same user\
`L1` ·
[answer](#q44.-wireless-throughput-is-much-lower-than-wired-for-the-same-user)

**Q45.** Guest Wi-Fi users can access internal VLANs unexpectedly\
`L2` ·
[answer](#q45.-guest-wi-fi-users-can-access-internal-vlans-unexpectedly)

**Q46.** Certain IoT devices fail to connect to a WPA2-Enterprise SSID\
`L2` ·
[answer](#q46.-certain-iot-devices-fail-to-connect-to-a-wpa2-enterprise-ssid)

**Q47.** After a wireless controller firmware update, multiple APs go
offline\
`L2` ·
[answer](#q47.-after-a-wireless-controller-firmware-update-multiple-aps-go-offline)

**Q48.** Users near the kitchen experience 2.4 GHz Wi-Fi dropouts\
`L1` ·
[answer](#q48.-users-near-the-kitchen-experience-2.4-ghz-wi-fi-dropouts)

**Q49.** Wi-Fi calling quality is choppy while data works fine\
`L2` ·
[answer](#q49.-wi-fi-calling-quality-is-choppy-while-data-works-fine)

## Chapter 6. Monitoring, Alerting and NOC Process

**Q50.** Monitoring floods with hundreds of alerts during a single
outage\
`L1` ·
[answer](#q50.-monitoring-floods-with-hundreds-of-alerts-during-a-single-outage)

**Q51.** A critical alert didn't page anyone during last night's outage\
`L2` ·
[answer](#q51.-a-critical-alert-didnt-page-anyone-during-last-nights-outage)

**Q52.** A flapping "interface down/up" alert every 5 minutes on a core
switch\
`L2` ·
[answer](#q52.-a-flapping-interface-downup-alert-every-5-minutes-on-a-core-switch)

**Q53.** Ticket volume for the same issue is coming in from multiple
sites\
`L1` ·
[answer](#q53.-ticket-volume-for-the-same-issue-is-coming-in-from-multiple-sites)

**Q54.** Monitoring shows 100% packet loss to a device users say is
working fine\
`L1` ·
[answer](#q54.-monitoring-shows-100-packet-loss-to-a-device-users-say-is-working-fine)

**Q55.** How do you decide whether to escalate or keep troubleshooting?\
`L1` ·
[answer](#q55.-how-do-you-decide-whether-to-escalate-or-keep-troubleshooting)

**Q56.** A maintenance window causes unexpected alerts to page on-call
staff\
`L1` ·
[answer](#q56.-a-maintenance-window-causes-unexpected-alerts-to-page-on-call-staff)

**Q57.** How do you document a resolved incident for future reference?\
`L1` ·
[answer](#q57.-how-do-you-document-a-resolved-incident-for-future-reference)

**Q58.** Bandwidth graphs show a steady climb toward saturation on a WAN
link\
`L2` ·
[answer](#q58.-bandwidth-graphs-show-a-steady-climb-toward-saturation-on-a-wan-link)

**Q59.** A P1 ticket sits untouched for 20 minutes because the engineer
is on break\
`L2` ·
[answer](#q59.-a-p1-ticket-sits-untouched-for-20-minutes-because-the-engineer-is-on-break)

**Q60.** Multiple monitoring tools report the same outage at different
severities\
`L2` ·
[answer](#q60.-multiple-monitoring-tools-report-the-same-outage-at-different-severities)

**Q61.** You've fixed an issue but the dashboard still shows red\
`L2` ·
[answer](#q61.-youve-fixed-an-issue-but-the-dashboard-still-shows-red)

**Q62.** Another team's change caused an outage and the NOC wasn't told\
`L2` ·
[answer](#q62.-another-teams-change-caused-an-outage-and-the-noc-wasnt-told)

**Q63.** Your shift is ending but an incident isn't resolved\
`L2` ·
[answer](#q63.-your-shift-is-ending-but-an-incident-isnt-resolved)

**Q64.** Configuration drift is causing repeat incidents across similar
devices\
`L2` ·
[answer](#q64.-configuration-drift-is-causing-repeat-incidents-across-similar-devices)

## Chapter 7. Cloud and Load Balancing

**Q65.** A load balancer keeps sending traffic to a backend server
that's down\
`L2` ·
[answer](#q65.-a-load-balancer-keeps-sending-traffic-to-a-backend-server-thats-down)

**Q66.** Users experience session drops with a round-robin load
balancer\
`L2` ·
[answer](#q66.-users-experience-session-drops-with-a-round-robin-load-balancer)

**Q67.** Cloud instances can't reach the internet despite having a
public IP\
`L2` ·
[answer](#q67.-cloud-instances-cant-reach-the-internet-despite-having-a-public-ip)

**Q68.** A hybrid cloud connection shows intermittent BGP flaps\
`L3` ·
[answer](#q68.-a-hybrid-cloud-connection-shows-intermittent-bgp-flaps)

**Q69.** An app in the cloud is reachable internally but not from
on-prem over VPN\
`L2` ·
[answer](#q69.-an-app-in-the-cloud-is-reachable-internally-but-not-from-on-prem-over-vpn)

**Q70.** Auto-scaling added instances but the load balancer isn't
sending them traffic\
`L2` ·
[answer](#q70.-auto-scaling-added-instances-but-the-load-balancer-isnt-sending-them-traffic)

**Q71.** Cross-region cloud traffic has unexpectedly high latency\
`L2` ·
[answer](#q71.-cross-region-cloud-traffic-has-unexpectedly-high-latency)

**Q72.** A security group update blocked traffic that used to work
through the NAT gateway\
`L3` ·
[answer](#q72.-a-security-group-update-blocked-traffic-that-used-to-work-through-the-nat-gateway)

## Chapter 8. VoIP and QoS

**Q73.** Calls are fine most of the day but become choppy around 5 PM\
`L2` ·
[answer](#q73.-calls-are-fine-most-of-the-day-but-become-choppy-around-5-pm)

**Q74.** One-way audio is reported on calls between two sites\
`L2` ·
[answer](#q74.-one-way-audio-is-reported-on-calls-between-two-sites)

**Q75.** VoIP quality complaints only come from wireless users, not
wired ones\
`L2` ·
[answer](#q75.-voip-quality-complaints-only-come-from-wireless-users-not-wired-ones)

**Q76.** Softphone calls drop at a precise repeating interval\
`L2` ·
[answer](#q76.-softphone-calls-drop-at-a-precise-repeating-interval)

**Q77.** After a WAN bandwidth upgrade, voice quality got worse\
`L2` ·
[answer](#q77.-after-a-wan-bandwidth-upgrade-voice-quality-got-worse)

**Q78.** Conference calls degrade only above about 10 participants\
`L2` ·
[answer](#q78.-conference-calls-degrade-only-above-about-10-participants)

## Chapter 9. Physical Layer and Cabling

**Q79.** A newly terminated cable passes a link light but has a high
error rate\
`L1` ·
[answer](#q79.-a-newly-terminated-cable-passes-a-link-light-but-has-a-high-error-rate)

**Q80.** A fibre link shows light-loss readings well beyond spec\
`L1` ·
[answer](#q80.-a-fibre-link-shows-light-loss-readings-well-beyond-spec)

**Q81.** A patch panel port works but the same run at the wall jack
doesn't\
`L1` ·
[answer](#q81.-a-patch-panel-port-works-but-the-same-run-at-the-wall-jack-doesnt)

**Q82.** A copper run works at 100 Mbps but fails at gigabit\
`L1` ·
[answer](#q82.-a-copper-run-works-at-100-mbps-but-fails-at-gigabit)

**Q83.** An SFP transceiver shows link down despite being properly
seated\
`L2` ·
[answer](#q83.-an-sfp-transceiver-shows-link-down-despite-being-properly-seated)

**Q84.** Multiple ports on the same switch card show errors after a
power event\
`L2` ·
[answer](#q84.-multiple-ports-on-the-same-switch-card-show-errors-after-a-power-event)

## Chapter 10. Escalation, ITIL and Communication

**Q85.** A vendor's ticket for a circuit outage isn't progressing\
`L2` ·
[answer](#q85.-a-vendors-ticket-for-a-circuit-outage-isnt-progressing)

**Q86.** You suspect another team's change caused an issue but they deny
it\
`L2` ·
[answer](#q86.-you-suspect-another-teams-change-caused-an-issue-but-they-deny-it)

**Q87.** How do you triage several simultaneous incidents with limited
staff?\
`L2` ·
[answer](#q87.-how-do-you-triage-several-simultaneous-incidents-with-limited-staff)

**Q88.** A recurring issue keeps getting temporary fixes\
`L2` · [answer](#q88.-a-recurring-issue-keeps-getting-temporary-fixes)

**Q89.** How do you communicate with stakeholders during a major
outage?\
`L2` ·
[answer](#q89.-how-do-you-communicate-with-stakeholders-during-a-major-outage)

**Q90.** A change you made caused unexpected downtime. What's your next
step?\
`L2` ·
[answer](#q90.-a-change-you-made-caused-unexpected-downtime.-whats-your-next-step)

**Q91.** How do you stay aware of network changes across departments?\
`L1` ·
[answer](#q91.-how-do-you-stay-aware-of-network-changes-across-departments)

## Chapter 11. Server and OS Networking

**Q92.** A Linux server can ping its gateway but not any other host\
`L2` ·
[answer](#q92.-a-linux-server-can-ping-its-gateway-but-not-any-other-host)

**Q93.** A Windows server loses connectivity right after an update\
`L2` ·
[answer](#q93.-a-windows-server-loses-connectivity-right-after-an-update)

**Q94.** Two NICs on a server in the same subnet cause intermittent
connectivity\
`L2` ·
[answer](#q94.-two-nics-on-a-server-in-the-same-subnet-cause-intermittent-connectivity)

**Q95.** A server's throughput is capped well below the NIC's rated
speed\
`L2` ·
[answer](#q95.-a-servers-throughput-is-capped-well-below-the-nics-rated-speed)

**Q96.** A hostname resolves fine but TLS certificate errors happen
intermittently\
`L2` ·
[answer](#q96.-a-hostname-resolves-fine-but-tls-certificate-errors-happen-intermittently)

## Chapter 12. Miscellaneous Protocols

**Q97.** Users complain email is delayed by up to an hour but eventually
delivers\
`L2` ·
[answer](#q97.-users-complain-email-is-delayed-by-up-to-an-hour-but-eventually-delivers)

**Q98.** FTP fails in passive mode through the firewall but works in
active mode\
`L2` ·
[answer](#q98.-ftp-fails-in-passive-mode-through-the-firewall-but-works-in-active-mode)

**Q99.** NTP sync failures are causing certificate and authentication
errors\
`L2` ·
[answer](#q99.-ntp-sync-failures-are-causing-certificate-and-authentication-errors)

**Q100.** SNMP polling fails for a subset of devices after a hardening
project\
`L2` ·
[answer](#q100.-snmp-polling-fails-for-a-subset-of-devices-after-a-hardening-project)

**Q101.** One particular TCP port randomly fails while others work\
`L3` ·
[answer](#q101.-one-particular-tcp-port-randomly-fails-while-others-work)

## Chapter 13. IPv6

**Q102.** A website is slow to load for some users but fine for others
on the same network\
`L2` ·
[answer](#q102.-a-website-is-slow-to-load-for-some-users-but-fine-for-others-on-the-same-network)

**Q103.** Clients have an IPv6 address but no IPv6 connectivity\
`L1` ·
[answer](#q103.-clients-have-an-ipv6-address-but-no-ipv6-connectivity)

**Q104.** Users on one VLAN suddenly lose connectivity after someone
plugs in a home router\
`L2` ·
[answer](#q104.-users-on-one-vlan-suddenly-lose-connectivity-after-someone-plugs-in-a-home-router)

**Q105.** Clients get an IPv6 address but no DNS server\
`L2` · [answer](#q105.-clients-get-an-ipv6-address-but-no-dns-server)

**Q106.** IPv6 connections hang on large transfers while small requests
work\
`L3` ·
[answer](#q106.-ipv6-connections-hang-on-large-transfers-while-small-requests-work)

**Q107.** A service you firewalled off is still reachable\
`L3` · [answer](#q107.-a-service-you-firewalled-off-is-still-reachable)

**Q108.** A hostname returns an AAAA record but the service is
unreachable\
`L1` ·
[answer](#q108.-a-hostname-returns-an-aaaa-record-but-the-service-is-unreachable)

## When you have finished

Score yourself in the [self-assessment
tracker](#appendix-c.-self-assessment-tracker), then go back to the
chapters where you scored lowest. Do not re-read the ones you already
know well, however satisfying that feels.

# Appendix C. Self-Assessment Tracker

Score yourself honestly before you interview. The scale is deliberately
harsh, because interview pressure removes roughly one level of
performance from everybody.

## The scale

  -----------------------------------------------------------------------
    Score What it means
  ------- ---------------------------------------------------------------
    **0** I do not recognise the scenario

    **1** I recognise it but cannot answer

    **2** I can state the likely cause

    **3** I can state the cause and the commands to confirm it

    **4** I can explain the mechanism and defend it under follow-up
          questioning

    **5** I have personally resolved this in production
  -----------------------------------------------------------------------

The jump that matters is **2 to 3, and then 3 to 4**. Most candidates
sit at 2, can name the cause, and fall apart on the first "why?" Getting
to 4 on your weak chapters is worth more than getting to 5 on your
strong ones.

## Be honest about the difference between 4 and 5

You will be asked "have you dealt with this yourself?" Answering 5 when
the truth is 4 is a bad trade, because the follow-up questions go
somewhere you cannot follow.

"I have not hit this in production, but I understand the mechanism and I
have built it in a lab" is a strong answer. An invented war story is
not, and it collapses immediately.

## Score sheet

Copy this table into a notebook, or photocopy the page, and fill it in.

  --------------------------------------------------------------------------------------------------------------------------
  Chapter                                                          Scenarios    Mix          Target   Target Your     Date
                                                                                                 L1       L2 score    
  ---------------------------------------------------------------- ------------ ---------- -------- -------- -------- ------
  [01 Routing and Switching](#chapter-1.-routing-and-switching)    Q1--Q14      5 L1 · 7          3        4          
                                                                                L2 · 2 L3                             

  [02 DNS and DHCP](#chapter-2.-dns-and-dhcp)                      Q15--Q22     4 L1 · 4          3        4          
                                                                                L2                                    

  [03 Firewall and Security](#chapter-3.-firewall-and-security)    Q23--Q34     9 L2 · 3          2        4          
                                                                                L3                                    

  [04 VPN and Remote Access](#chapter-4.-vpn-and-remote-access)    Q35--Q41     1 L1 · 6          3        4          
                                                                                L2                                    

  [05 Wireless](#chapter-5.-wireless)                              Q42--Q49     2 L1 · 6          3        4          
                                                                                L2                                    

  [06 Monitoring, Alerting and NOC                                 Q50--Q64     6 L1 · 9          3        4          
  Process](#chapter-6.-monitoring-alerting-and-noc-process)                     L2                                    

  [07 Cloud and Load                                               Q65--Q72     6 L2 · 2          2        4          
  Balancing](#chapter-7.-cloud-and-load-balancing)                              L3                                    

  [08 VoIP and QoS](#chapter-8.-voip-and-qos)                      Q73--Q78     6 L2              2        4          

  [09 Physical Layer and                                           Q79--Q84     4 L1 · 2          3        4          
  Cabling](#chapter-9.-physical-layer-and-cabling)                              L2                                    

  [10 Escalation, ITIL and                                         Q85--Q91     1 L1 · 6          3        4          
  Communication](#chapter-10.-escalation-itil-and-communication)                L2                                    

  [11 Server and OS                                                Q92--Q96     5 L2              2        4          
  Networking](#chapter-11.-server-and-os-networking)                                                                  

  [12 Miscellaneous                                                Q97--Q101    4 L2 · 1          2        4          
  Protocols](#chapter-12.-miscellaneous-protocols)                              L3                                    

  [13 IPv6](#chapter-13.-ipv6)                                     Q102--Q108   2 L1 · 3          3        4          
                                                                                L2 · 2 L3                             
  --------------------------------------------------------------------------------------------------------------------------

## How to read your scores

**Anything below its target** is where your revision time belongs. Not
the chapters you enjoy.

**Anything at 4 that you have never actually done** deserves a lab
session before the interview. The mechanism knowledge is real, but the
experience question is coming.

**Anything at 0 or 1** in a chapter relevant to the role you are
applying for is a red flag worth addressing first, even if it is
uncomfortable. A single confident "I do not know that area at all" is
survivable. Three of them is not.

## Re-score after two weeks

Scores taken immediately after reading a chapter are inflated, because
the material is still in short-term memory. Score once after reading,
then again two weeks later without revisiting. The second number is the
real one, and the gap between them tells you what needs spaced
repetition rather than another read-through.

# Appendix D. Command Reference

Every command carries a safety label. Read it before pasting anything
into a production device.

  -----------------------------------------------------------------------------
  Label                 Meaning
  --------------------- -------------------------------------------------------
  `read-only`           Displays state. Safe on production.

  `active test`         Generates traffic or probes. Low risk, but visible in
                        logs and may trigger security alerts.

  `service-affecting`   Can interrupt traffic. Needs a maintenance window.

  `change approval`     Modifies configuration. Needs change control and a
                        rollback plan.
  -----------------------------------------------------------------------------

**On "exact" commands.** Syntax and defaults vary by platform and
software release. Commands below were written against the platforms
listed in the [review status](#review-status-and-tested-platforms).
Anything you have not personally verified on your own release should be
treated as a **pattern to adapt**, not as text to paste. That
distinction is deliberate, and it is the honest position for a guide
maintained by one author.

## Cisco IOS and IOS XE

### Interface and physical layer

                                                         [read-only]
    show interface <if>                    counters, errors, duplex, load
    show interface status                  negotiated speed and duplex
    show interface counters errors         CRC, alignment, symbol errors
    show interface transceiver detail      optical Tx/Rx in dBm, thresholds
    show interface trunk                   allowed and active VLANs
    show interface <if> capabilities
    show power inline                      PoE draw and budget

                                                         [read-only, resets state]
    clear counters <if>                    reset before measuring a rate

### Layer 2

                                                         [read-only]
    show mac address-table
    show mac address-table address <mac>   is one MAC on two ports?
    show spanning-tree detail              last topology change and its port
    show spanning-tree inconsistentports   guard violations
    show etherchannel summary              P bundled, s suspended, I individual
    show etherchannel load-balance
    show cdp neighbors detail              what is on the other end?
    show lldp neighbors detail
    show vlan brief

### Layer 3 and routing

                                                         [read-only]
    show ip route <destination>            the route that WILL be used
    show ip route <prefix> longer-prefixes
    show ip cef exact-route <src> <dst>    which ECMP path a flow takes
    show ip arp
    show ip ospf neighbor                  the STATE names the fault
    show ip ospf interface <if>            area, timers, MTU, auth
    show bgp ipv4 unicast summary
    show bgp neighbor <ip> received-routes needs soft-reconfig or refresh
    show bgp neighbor <ip> advertised-routes
    show bgp ipv4 unicast <prefix>         why it won or lost best-path
    show standby brief                     HSRP state and priority
    show vrrp brief
    show track                             is anything actually tracked?
    show bfd neighbors detail

### IPv6

                                                         [read-only]
    show ipv6 interface brief
    show ipv6 interface <if>               RA settings, M/O flags, lifetime
    show ipv6 route
    show ipv6 neighbors
    show ipv6 routers                      what RAs is this device seeing?
    show ipv6 access-list                  does an IPv6 policy exist at all?

### Control plane and platform

                                                         [read-only]
    show processes cpu sorted | exclude 0.00
    show processes cpu history             5-second, 1-minute, 72-hour graphs
    show ip cef                            CEF enabled and populated?
    show controllers cpu-interface         punted packet counters
    show policy-map control-plane          CoPP drops
    show environment all
    show power status
    show diagnostic result module <n> detail
    show inventory
    show logging | include <keyword>

### QoS

                                                         [read-only]
    show policy-map interface <wan-if>     priority queue drops
    show mls qos interface <if>            trust boundary state
    show run interface <if> | include bandwidth|service-policy

### Testing and debugging

                                                         [active test]
    ping <dest> repeat 100 size 1500 df-bit
    traceroute <dest>

                                                         [service-affecting]
    debug ip ospf adj
    debug crypto ikev2
    debug capwap client events
    ! Always: terminal monitor, then undebug all when finished.
    ! debug output on a loaded control plane has taken routers down.

### Change safety

                                                         [change approval]
    archive
      path <secure-transfer-target>        SCP or SFTP, never TFTP
      write-memory
      log config
        logging enable
        notify syslog

    configure replace flash:pre-change.cfg force
    configure terminal revert timer 5      IOS XE auto-revert

## Cisco ASA

                                                         [read-only]
    packet-tracer input <if> tcp <src> <sport> <dst> <dport> detailed
    show access-list <name> | include hitcnt
    show conn address <ip>
    show nat detail
    show xlate
    show asp drop                          accelerated path drop reasons
    show crypto ikev2 sa                   Phase 1
    show crypto ipsec sa                   Phase 2: compare encaps vs decaps
    show vpn-sessiondb detail anyconnect
    show service-policy inspect sip
    show run timeout

`packet-tracer` is the first command to learn on this platform. Run it
from the interface the traffic actually enters, with the real source
address.

## Palo Alto

                                                         [read-only]
    test security-policy-match from <zone> to <zone> source <ip> \
         destination <ip> protocol 6 destination-port 443
    show session all filter source <ip>
    show session info                      session count vs platform maximum
    show system resources follow
    show running resource-monitor hour
    show vpn ike-sa ; show vpn ipsec-sa ; show vpn flow
    show log url query equal "( addr.src eq <ip> )"
    show log decryption

## Fortinet

                                                         [read-only]
    get system performance status
    diagnose sys session stat
    diagnose sys session list
    diagnose npu npu-feature               is hardware offload engaged?

                                                         [service-affecting]
    diagnose debug flow filter addr <ip>
    diagnose debug flow trace start 20
    diagnose debug application urlfilter -1
    diagnose debug disable                 always turn it off afterwards

## Cisco Wireless LAN Controller

                                                         [read-only]
    show ap join stats summary all
    show ap join stats detailed <ap-mac>   names the join failure reason
    show ap auto-rf <ap-name>              channel, power, noise, interference
    show ap uptime <ap-name>               has it been rebooting?
    show ap image all
    show client detail <mac>               RSSI, SNR, retries, data rate, AC
    show ap dot11 5ghz summary             utilisation and client count
    show wlan <id>                         VLAN mapping, WMM, 11k/v/r
    show mobility anchor
    show time                              cert validation depends on it

                                                         [service-affecting]
    debug client <mac>
    debug capwap client events
    debug pm pki enable

## Linux

### Addressing and routing

                                                        # [read-only]
    ip addr show
    ip route show
    ip route get 8.8.8.8            # the route AND source address that will be used
    ip neigh show                   # ARP cache
    ip -6 addr show
    ip -6 route show
    ip -6 neigh show

`ip`` route get` is the command to learn first here. It answers in one
line what reading the routing table and reasoning about it takes several
minutes to work out.

### Interface and performance

                                                        # [read-only]
    ethtool eth0                    # speed, duplex, link
    ethtool -S eth0                 # per-queue statistics and drops
    ethtool -k eth0                 # offload settings
    ethtool -g eth0                 # ring buffer sizes
    ss -tulpn                       # listening sockets
    ss -ti                          # per-socket cwnd, rtt, retransmits
    ss -s                           # socket summary
    netstat -s | grep -i -E "listen|overflow|drop"
    mpstat -P ALL 1                 # is one core pinned?

### Firewall

                                                        # [read-only]
    iptables -L -v -n
    nft list ruleset
    firewall-cmd --list-all
    sysctl net.ipv4.conf.all.rp_filter
    sysctl net.ipv4.conf.all.arp_ignore
    sysctl net.ipv4.conf.all.arp_announce

### Diagnosis

                                                        # [active test]
    mtr -rwzc 100 <host>            # loss and latency per hop; run from both ends
    traceroute -n <host>
    tracepath <host>                # reports path MTU changes
    tracepath6 <host>
    ping -M do -s 1472 <dest>       # DF-bit test, IPv4
    ping6 -M do -s 1452 <dest>      # DF-bit test, IPv6
    iperf3 -c <server> -t 30        # single stream
    iperf3 -c <server> -t 30 -P 8   # parallel: isolates per-flow limits
    tcpdump -i any -n "host <ip> and port <p>" -w capture.pcap

### DNS

                                                        # [active test]
    dig <name>
    dig <name> +trace               # walk the delegation from the root
    dig @<server> <name> +norecurse
    dig <name> +tcp                 # does TCP 53 work?
    dig <name> +bufsize=4096        # large EDNS0 response
    dig <name> +dnssec              # validation behaviour
    dig <name> +cd                  # checking disabled, isolates DNSSEC
    dig MX <domain> ; dig TXT <domain> ; dig -x <ip>

### TLS

                                                        # [active test]
    openssl s_client -connect <host>:443 -showcerts
    openssl s_client -connect <ip>:443 -servername <host> </dev/null 2>/dev/null \
      | openssl x509 -noout -serial -subject -dates -ext subjectAltName

### Time

                                                        # [read-only]
    timedatectl status
    chronyc tracking ; chronyc sources -v
    ntpq -p

## Windows and PowerShell

                                                        # [read-only]
    Get-NetAdapter | Select Name, Status, LinkSpeed, DriverVersion, DriverDate
    Get-NetIPConfiguration
    Get-NetIPInterface | Sort InterfaceMetric
    Get-NetRoute
    Get-NetRoute -AddressFamily IPv6
    Get-NetConnectionProfile                # Domain, Private or Public
    Get-NetFirewallProfile
    Get-NetLbfoTeam                         # did teaming survive?
    Get-NetTCPConnection -State Listen

                                                        # [active test]
    Test-NetConnection <host> -Port 443 -InformationLevel Detailed
    Resolve-DnsName <name> -Server <dns>
    nslookup <name> <dns-server>

                                                        # [read-only]
    Get-DnsClientServerAddress
    Get-DnsClientNrptPolicy                 # split DNS rules
    w32tm /query /status                    # NTP state
    w32tm /stripchart /computer:<dc> /samples:5
    nltest /dsgetdc:<domain>
    Get-WinEvent -FilterHashtable @{LogName='Security';Id=4625}
    Get-HotFix | Sort InstalledOn -Descending | Select -First 10

**A caution on** `Set-``NetConnectionProfile`**.** You cannot force the
domain profile with this cmdlet. Windows assigns it automatically once
Network Location Awareness authenticates against a domain controller. If
a machine has dropped to Public, fix DNS and domain controller
reachability instead of trying to override the category. See
[Q93](#q93.-a-windows-server-loses-connectivity-right-after-an-update).

### Windows DHCP and DNS server

                                                        # [read-only]
    Get-DhcpServerv4Scope
    Get-DhcpServerv4ScopeStatistics
    Get-DhcpServerv4Lease -ScopeId <x> | Group-Object ClientId
    Get-DnsServerZone
    Get-DnsServerForwarder
    Get-DnsServerResourceRecord -ZoneName <zone> -Name <host>
    Clear-DnsServerCache

## AWS CLI

                                                        # [read-only]
    aws ec2 describe-route-tables \
      --filters Name=association.subnet-id,Values=<subnet>
    aws ec2 describe-internet-gateways \
      --filters Name=attachment.vpc-id,Values=<vpc>
    aws ec2 describe-security-groups --group-ids <sg>
    aws ec2 describe-network-acls \
      --filters Name=association.subnet-id,Values=<subnet>
    aws ec2 describe-nat-gateways --nat-gateway-ids <nat>
    aws ec2 describe-vpn-connections --vpn-connection-ids <vpn>

    aws elbv2 describe-target-health --target-group-arn <arn>
    aws elbv2 describe-target-group-attributes --target-group-arn <arn>
    aws autoscaling describe-auto-scaling-groups --auto-scaling-group-names <asg>
    aws autoscaling describe-auto-scaling-activities --auto-scaling-group-name <asg>

    # Reachability Analyzer: answers "what is blocking this?" definitively
    aws ec2 create-network-insights-path ...
    aws ec2 start-network-insights-analysis ...

**Flow logs.** `aws`` ec2 describe-flow-logs` lists flow log
**configurations**. It does not return records. To read actual REJECT
entries you must query the destination:

                                                        # [read-only]
    aws logs start-query \
      --log-group-name <flow-log-group> \
      --start-time <epoch> --end-time <epoch> \
      --query-string 'fields srcAddr, dstAddr, dstPort, action
                      | filter action = "REJECT"
                      | sort @timestamp desc | limit 50'
    # Or query S3-delivered logs with Athena.

## Handling credentials safely

Several commands here take community strings, pre-shared keys or
passwords. Three rules:

1.  **Never paste live credentials into tickets, chat or screenshots.**
    Reference the credential store instead.
2.  **Prefer SNMPv3 and SSH** over SNMPv2c and Telnet. The older
    protocols carry credentials in clear text and a packet capture
    reveals them.
3.  **Back up configurations over SCP, SFTP or HTTPS**, never TFTP.
    Device configurations contain SNMP strings, pre-shared keys and
    password hashes, so treat the backup repository as a secret store
    rather than a file share.

# Appendix E. Ports, Protocols and Markings

## Ports worth knowing by heart

  ----------------------------------------------------------------------------------------------------------------------------
  Service    Port           Transport   Why it matters in a NOC
  ---------- -------------- ----------- --------------------------------------------------------------------------------------
  FTP        21             TCP         The data channel is separate. See
  control                               [Q98](#q98.-ftp-fails-in-passive-mode-through-the-firewall-but-works-in-active-mode)

  FTP data   20             TCP         Server initiates back to the client
  (active)                              

  SSH, SCP,  22             TCP         Management baseline. Use this, not Telnet
  SFTP                                  

  Telnet     23             TCP         Clear text. Should be disabled everywhere

  SMTP       25             TCP         Frequently blocked outbound by ISPs

  DNS        53             UDP **and** TCP is required for large responses. Policies that permit only UDP cause
                            TCP         [Q16](#q16.-internal-dns-resolves-fine-but-external-domains-fail-intermittently)

  DHCP       67 server, 68  UDP         Broadcast. Needs a relay to cross a router
             client                     

  TFTP       69             UDP         No auth, no encryption. Do not use for config backup

  HTTP       80             TCP         

  Kerberos   88             TCP + UDP   Time-sensitive. Breaks when clocks drift. See
                                        [Q99](#q99.-ntp-sync-failures-are-causing-certificate-and-authentication-errors)

  NTP        123            UDP         Blocking it breaks TLS and Kerberos, not just clocks

  NetBIOS    137--139       TCP + UDP   Legacy Windows name services

  SNMP       161 poll, 162  UDP         See
             trap                       [Q100](#q100.-snmp-polling-fails-for-a-subset-of-devices-after-a-hardening-project)

  BGP        179            TCP         Sessions drop on sustained keepalive loss. See
                                        [Q68](#q68.-a-hybrid-cloud-connection-shows-intermittent-bgp-flaps)

  LDAP /     389 / 636      TCP         Directory authentication
  LDAPS                                 

  HTTPS      443            TCP         Also the fallback transport for TLS-based VPN

  SMB        445            TCP         File shares. See
                                        [Q35](#q35.-a-remote-worker-connects-to-vpn-but-cant-access-internal-file-shares)

  Syslog     514            UDP         6514 for syslog over TLS

  IKE        500            UDP         IPsec phase 1

  RADIUS     1812 auth,     UDP         802.1X and NAC
             1813 acct                  

  NAT-T      4500           UDP         Required when a peer is behind NAT
  (IPsec)                               

  CAPWAP     5246 control,  UDP         Lightweight AP to controller. See
             5247 data                  [Q47](#q47.-after-a-wireless-controller-firmware-update-multiple-aps-go-offline)

  SIP        5060, 5061 TLS TCP + UDP   Signalling only. Media is separate

  RTP media  16384--32768   UDP         Range varies by vendor. See
             typical                    [Q74](#q74.-one-way-audio-is-reported-on-calls-between-two-sites)

  QUIC /     443            **UDP**     Increasingly common. Policies permitting only TCP 443 silently force fallback
  HTTP/3                                
  ----------------------------------------------------------------------------------------------------------------------------

### Modern additions worth knowing

  -------------------------------------------------------------------------
  Service       Port   Note
  ------------- ------ ----------------------------------------------------
  DNS over TLS  853    TCP. Easy to identify and block by port
  (DoT)                

  DNS over      443    Indistinguishable from web traffic. Bypasses your
  HTTPS (DoH)          DNS filtering entirely unless you manage the client

  DNS over QUIC 853    UDP
  (DoQ)                

  HTTP/3        443    Over QUIC on UDP
  -------------------------------------------------------------------------

**Why this matters operationally.** A browser configured for DNS over
HTTPS ignores the resolver you handed out via DHCP, which means your
internal names may not resolve and your DNS-based filtering and logging
see nothing. If your organisation relies on DNS policy as a control, DoH
is a gap to manage deliberately rather than discover during an incident.

QUIC matters for a different reason. It runs over UDP 443, so a firewall
permitting only TCP 443 causes clients to fall back to TCP after a
delay. The symptom is "the internet feels slow" with nothing in the
logs, which is the same shape as
[Q102](#q102.-a-website-is-slow-to-load-for-some-users-but-fine-for-others-on-the-same-network).

## IP protocol numbers

These appear in ACLs and firewall rules where a port number would not
apply.

  -----------------------------------------------------------------------
  Protocol     Number       Note
  ------------ ------------ ---------------------------------------------
  ICMP         1            

  TCP          6            

  UDP          17           

  GRE          47           Tunnelling. Adds 24 bytes of overhead

  ESP          50           IPsec encrypted payload

  AH           51           IPsec authentication header

  OSPF         89           

  VRRP         112          

  ICMPv6       58           **Do not blanket-block this.** See below
  -----------------------------------------------------------------------

## ICMPv6 message types you must permit

In IPv4, filtering ICMP is unwise. In IPv6 it breaks the protocol,
because Neighbour Discovery and path MTU discovery both run over ICMPv6.

  ----------------------------------------------------------------------------------------------------------------
  Type    Message              Consequence of blocking
  ------- -------------------- -----------------------------------------------------------------------------------
  1       Destination          Poor error reporting, slow failures
          unreachable          

  **2**   **Packet too big**   **Path MTU discovery dies. Large transfers hang.** See
                               [Q106](#q106.-ipv6-connections-hang-on-large-transfers-while-small-requests-work)

  3       Time exceeded        Traceroute stops working

  4       Parameter problem    Poor error reporting

  133     Router solicitation  Hosts cannot discover routers

  134     Router advertisement No address, no gateway

  135     Neighbour            No address resolution at all
          solicitation         

  136     Neighbour            No address resolution at all
          advertisement        

  137     Redirect             Suboptimal routing
  ----------------------------------------------------------------------------------------------------------------

Types 133 to 137 should be permitted on-link and generally not forwarded
across boundaries. Type 2 must be permitted end to end.

Full guidance is in [RFC
4890](https://www.rfc-editor.org/rfc/rfc4890.html), which is the
document to cite if anyone insists on blocking ICMPv6 wholesale.

## DSCP values and QoS markings

This table is where a lot of published material goes wrong, so read the
note underneath before using it.

### RFC 4594 service classes

  ------------------------------------------------------------------------
  Traffic                 DSCP            Decimal RFC 4594 service class
  ----------------------- ------------ ---------- ------------------------
  Network control         CS6                  48 Network Control

  Telephony (voice media) EF                   46 Telephony

  **Signalling**          **CS5**          **40** **Signaling**

  Multimedia conferencing AF41--AF43   34, 36, 38 Multimedia Conferencing

  Real-time interactive   CS4                  32 Real-Time Interactive

  Multimedia streaming    AF31--AF33   26, 28, 30 Multimedia Streaming

  Broadcast video         CS3                  24 Broadcast Video

  Low-latency data        AF21--AF23   18, 20, 22 Low-Latency Data

  OAM                     CS2                  16 OAM

  High-throughput data    AF11--AF13   10, 12, 14 High-Throughput Data

  Standard                DF                    0 Standard

  Low-priority data       CS1                   8 Low-Priority Data
  ------------------------------------------------------------------------

### About call signalling specifically

You will see **AF31 described as call signalling** in a great deal of
documentation and in older Cisco design guides. Be careful with it.

- **RFC 4594** assigns **CS5** to its Signaling service class, and uses
  **AF31 for Multimedia Streaming**.
- **Cisco's older QoS baseline** used **AF31** for call signalling,
  which is where the widespread convention came from.
- **Cisco's later enterprise medianet models** moved signalling to
  **CS3**, aligning more closely with RFC 4594.

All three exist in production networks today. None of them is
universally "correct."

**What to do about it.** State which profile your network follows,
document it, and apply it consistently end to end. In an interview,
saying "we mark signalling CS3 following the Cisco enterprise model,
though RFC 4594 specifies CS5 and older designs used AF31" is a much
stronger answer than confidently asserting any single value.

The value that is genuinely consistent everywhere is **EF (46) for voice
media**. That one you can rely on.

## Voice quality targets

Worth memorising, because they turn a vague complaint into a measurable
fact.

  ------------------------------------------------------------------------
  Metric              Target              Beyond it
  ------------------- ------------------- --------------------------------
  One-way latency     under 150 ms        People talk over each other

  Jitter              under 30 ms         Choppy, robotic audio

  Packet loss         under 1 percent     Dropouts and clipped words
  ------------------------------------------------------------------------

Source: [ITU-T G.114](https://www.itu.int/rec/T-REC-G.114) for latency,
[RFC 4594](https://www.rfc-editor.org/rfc/rfc4594.html) for the service
class targets.

## Wireless thresholds

  ------------------------------------------------------------------------
  Metric               Data                  Voice
  -------------------- --------------------- -----------------------------
  RSSI                 better than -70 dBm   better than -67 dBm

  SNR                  20 dB or better       25 dB or better

  Retries              under 15 percent      under 10 percent

  Channel utilisation  under 50 percent      under 40 percent

  Roam time            not critical          under 50 ms, needs 802.11r
  ------------------------------------------------------------------------

## Useful numbers

**Encapsulation overhead**

  -----------------------------------------------------------------------
  Encapsulation                                               Bytes added
  ---------------------------------------- ------------------------------
  GRE                                                                  24

  IPsec ESP tunnel mode                                  roughly 50 to 60

  NAT-T (UDP 4500)                                                      8

  VXLAN                                                                50

  802.1Q VLAN tag                                                       4
  -----------------------------------------------------------------------

**MTU reference points**

  -----------------------------------------------------------------------
               Value Meaning
  ------------------ ----------------------------------------------------
                1500 Standard Ethernet payload

                1492 PPPoE

         1400 / 1360 Common tunnel MTU / TCP MSS clamp

                1280 IPv6 minimum link MTU. Safe fallback

                9000 Typical jumbo frame
  -----------------------------------------------------------------------

**Optical loss budget**

  -----------------------------------------------------------------------
  Element                                  Typical loss
  ---------------------------------------- ------------------------------
  Mated connector pair                     0.3 to 0.75 dB

  Fusion splice                            around 0.1 dB

  Multi-mode fibre at 850 nm               around 3.0 dB per km

  Single-mode fibre at 1310 nm             around 0.4 dB per km
  -----------------------------------------------------------------------

**Propagation delay**

Light in fibre travels at roughly **200 km per millisecond**.

    round-trip distance (km) / 200 = minimum round-trip time (ms)

A 15,000 km round trip cannot be faster than about **75 ms** of pure
propagation. Real routes are longer than straight-line distance and
equipment adds more, so 90 to 110 ms would be normal. Work this out
before escalating a latency complaint to a carrier.

# Appendix F. Standards Index

Every standard referenced in this guide, grouped by topic. Links go to
the primary source.

**Why primary sources matter.** A great deal of published networking
material repeats claims that were true once, true for one vendor, or
never true. The RFC or the IEEE document is what actually governs the
behaviour. When something in this guide disagrees with a standard listed
here, the standard is right and this guide has an error worth
[reporting](#feedback).

## Core protocols

  ----------------------------------------------------------------------------------------------------------
  Topic                                                 Reference
  ----------------------------------------------------- ----------------------------------------------------
  Internet Protocol                                     [RFC
                                                        791](https://www.rfc-editor.org/rfc/rfc791.html)

  ICMP                                                  [RFC
                                                        792](https://www.rfc-editor.org/rfc/rfc792.html)

  TCP (current specification)                           [RFC
                                                        9293](https://www.rfc-editor.org/rfc/rfc9293.html)

  ARP                                                   [RFC
                                                        826](https://www.rfc-editor.org/rfc/rfc826.html)

  Private address space                                 [RFC
                                                        1918](https://www.rfc-editor.org/rfc/rfc1918.html)

  Requirements for Internet hosts                       [RFC
                                                        1122](https://www.rfc-editor.org/rfc/rfc1122.html)

  Requirements for IPv4 routers                         [RFC
                                                        1812](https://www.rfc-editor.org/rfc/rfc1812.html)

  TCP extensions for high performance                   [RFC
                                                        7323](https://www.rfc-editor.org/rfc/rfc7323.html)

  HTTP semantics                                        [RFC
                                                        9110](https://www.rfc-editor.org/rfc/rfc9110.html)

  HTTP state management (cookies)                       [RFC
                                                        6265](https://www.rfc-editor.org/rfc/rfc6265.html)
  ----------------------------------------------------------------------------------------------------------

## MTU and fragmentation

  ------------------------------------------------------------------------------------------------------------
  Topic                                                   Reference
  ------------------------------------------------------- ----------------------------------------------------
  Path MTU Discovery                                      [RFC
                                                          1191](https://www.rfc-editor.org/rfc/rfc1191.html)

  TCP problems with PMTUD                                 [RFC
                                                          2923](https://www.rfc-editor.org/rfc/rfc2923.html)

  Packetization Layer PMTUD                               [RFC
                                                          4821](https://www.rfc-editor.org/rfc/rfc4821.html)

  MTU and fragmentation issues with tunnels               [RFC
                                                          4459](https://www.rfc-editor.org/rfc/rfc4459.html)

  Path MTU Discovery for IPv6                             [RFC
                                                          8201](https://www.rfc-editor.org/rfc/rfc8201.html)
  ------------------------------------------------------------------------------------------------------------

## Routing

  ---------------------------------------------------------------------------------------------------------
  Topic                                                Reference
  ---------------------------------------------------- ----------------------------------------------------
  OSPFv2                                               [RFC
                                                       2328](https://www.rfc-editor.org/rfc/rfc2328.html)

  BGP-4                                                [RFC
                                                       4271](https://www.rfc-editor.org/rfc/rfc4271.html)

  BGP operations and security                          [RFC
                                                       7454](https://www.rfc-editor.org/rfc/rfc7454.html)

  Bidirectional Forwarding Detection                   [RFC
                                                       5880](https://www.rfc-editor.org/rfc/rfc5880.html)

  VRRPv3                                               [RFC
                                                       5798](https://www.rfc-editor.org/rfc/rfc5798.html)

  Protecting the router control plane                  [RFC
                                                       6192](https://www.rfc-editor.org/rfc/rfc6192.html)
  ---------------------------------------------------------------------------------------------------------

## DNS

  --------------------------------------------------------------------------------------------------------
  Topic                                               Reference
  --------------------------------------------------- ----------------------------------------------------
  Domain names: concepts                              [RFC
                                                      1034](https://www.rfc-editor.org/rfc/rfc1034.html)

  Domain names: implementation                        [RFC
                                                      1035](https://www.rfc-editor.org/rfc/rfc1035.html)

  DNS terminology                                     [RFC
                                                      8499](https://www.rfc-editor.org/rfc/rfc8499.html)

  EDNS(0)                                             [RFC
                                                      6891](https://www.rfc-editor.org/rfc/rfc6891.html)

  DNS transport over TCP                              [RFC
                                                      7766](https://www.rfc-editor.org/rfc/rfc7766.html)

  DNSSEC protocol modifications                       [RFC
                                                      4035](https://www.rfc-editor.org/rfc/rfc4035.html)

  Dynamic updates in the DNS                          [RFC
                                                      2136](https://www.rfc-editor.org/rfc/rfc2136.html)

  Serving stale data                                  [RFC
                                                      8767](https://www.rfc-editor.org/rfc/rfc8767.html)

  DNS extensions to support IPv6                      [RFC
                                                      3596](https://www.rfc-editor.org/rfc/rfc3596.html)
  --------------------------------------------------------------------------------------------------------

## DHCP and addressing

  ----------------------------------------------------------------------------------------------------------
  Topic                                                 Reference
  ----------------------------------------------------- ----------------------------------------------------
  DHCP                                                  [RFC
                                                        2131](https://www.rfc-editor.org/rfc/rfc2131.html)

  DHCP relay agent information option                   [RFC
                                                        3046](https://www.rfc-editor.org/rfc/rfc3046.html)

  IPv4 link-local addresses (APIPA)                     [RFC
                                                        3927](https://www.rfc-editor.org/rfc/rfc3927.html)

  DHCPv6                                                [RFC
                                                        8415](https://www.rfc-editor.org/rfc/rfc8415.html)
  ----------------------------------------------------------------------------------------------------------

## IPv6

  -------------------------------------------------------------------------------------------------------------
  Topic                                                    Reference
  -------------------------------------------------------- ----------------------------------------------------
  IPv6 specification                                       [RFC
                                                           8200](https://www.rfc-editor.org/rfc/rfc8200.html)

  Neighbor Discovery for IPv6                              [RFC
                                                           4861](https://www.rfc-editor.org/rfc/rfc4861.html)

  IPv6 stateless address autoconfiguration                 [RFC
                                                           4862](https://www.rfc-editor.org/rfc/rfc4862.html)

  Default address selection for IPv6                       [RFC
                                                           6724](https://www.rfc-editor.org/rfc/rfc6724.html)

  Happy Eyeballs version 2                                 [RFC
                                                           8305](https://www.rfc-editor.org/rfc/rfc8305.html)

  RA options for DNS configuration                         [RFC
                                                           8106](https://www.rfc-editor.org/rfc/rfc8106.html)

  Rogue IPv6 RA problem statement                          [RFC
                                                           6104](https://www.rfc-editor.org/rfc/rfc6104.html)

  IPv6 Router Advertisement Guard                          [RFC
                                                           6105](https://www.rfc-editor.org/rfc/rfc6105.html)

  Filtering ICMPv6 messages in firewalls                   [RFC
                                                           4890](https://www.rfc-editor.org/rfc/rfc4890.html)

  Security implications of IPv6 on IPv4 networks           [RFC
                                                           7123](https://www.rfc-editor.org/rfc/rfc7123.html)

  Operational security considerations for IPv6             [RFC
                                                           9099](https://www.rfc-editor.org/rfc/rfc9099.html)
  -------------------------------------------------------------------------------------------------------------

## Security, VPN and PKI

  ------------------------------------------------------------------------------------------------------------
  Topic                                                   Reference
  ------------------------------------------------------- ----------------------------------------------------
  IKEv2                                                   [RFC
                                                          7296](https://www.rfc-editor.org/rfc/rfc7296.html)

  Security architecture for IP                            [RFC
                                                          4301](https://www.rfc-editor.org/rfc/rfc4301.html)

  IP Encapsulating Security Payload                       [RFC
                                                          4303](https://www.rfc-editor.org/rfc/rfc4303.html)

  NAT traversal negotiation in IKE                        [RFC
                                                          3947](https://www.rfc-editor.org/rfc/rfc3947.html)

  UDP encapsulation of IPsec ESP                          [RFC
                                                          3948](https://www.rfc-editor.org/rfc/rfc3948.html)

  IKEv2 fragmentation                                     [RFC
                                                          7383](https://www.rfc-editor.org/rfc/rfc7383.html)

  Split DNS configuration for IKEv2                       [RFC
                                                          8598](https://www.rfc-editor.org/rfc/rfc8598.html)

  Traditional IP NAT                                      [RFC
                                                          3022](https://www.rfc-editor.org/rfc/rfc3022.html)

  NAT behavioural requirements for UDP                    [RFC
                                                          4787](https://www.rfc-editor.org/rfc/rfc4787.html)

  NAT behavioural requirements for TCP                    [RFC
                                                          5382](https://www.rfc-editor.org/rfc/rfc5382.html)

  X.509 certificate and CRL profile                       [RFC
                                                          5280](https://www.rfc-editor.org/rfc/rfc5280.html)

  Service identity verification                           [RFC
                                                          6125](https://www.rfc-editor.org/rfc/rfc6125.html)

  TLS extensions including SNI                            [RFC
                                                          6066](https://www.rfc-editor.org/rfc/rfc6066.html)

  TLS 1.3                                                 [RFC
                                                          8446](https://www.rfc-editor.org/rfc/rfc8446.html)

  EAP                                                     [RFC
                                                          3748](https://www.rfc-editor.org/rfc/rfc3748.html)

  EAP-TLS                                                 [RFC
                                                          5216](https://www.rfc-editor.org/rfc/rfc5216.html)

  Kerberos V5                                             [RFC
                                                          4120](https://www.rfc-editor.org/rfc/rfc4120.html)

  Firewall behaviour and requirements                     [RFC
                                                          2979](https://www.rfc-editor.org/rfc/rfc2979.html)

  Effects of pervasive encryption on operators            [RFC
                                                          8404](https://www.rfc-editor.org/rfc/rfc8404.html)

  Captive portal architecture                             [RFC
                                                          8952](https://www.rfc-editor.org/rfc/rfc8952.html)
  ------------------------------------------------------------------------------------------------------------

## Voice, video and QoS

  -------------------------------------------------------------------------------------------------------
  Topic                                              Reference
  -------------------------------------------------- ----------------------------------------------------
  SIP                                                [RFC
                                                     3261](https://www.rfc-editor.org/rfc/rfc3261.html)

  SDP                                                [RFC
                                                     4566](https://www.rfc-editor.org/rfc/rfc4566.html)

  RTP                                                [RFC
                                                     3550](https://www.rfc-editor.org/rfc/rfc3550.html)

  RTP topologies                                     [RFC
                                                     7667](https://www.rfc-editor.org/rfc/rfc7667.html)

  Session timers in SIP                              [RFC
                                                     4028](https://www.rfc-editor.org/rfc/rfc4028.html)

  DiffServ field definition                          [RFC
                                                     2474](https://www.rfc-editor.org/rfc/rfc2474.html)

  DiffServ service class guidelines                  [RFC
                                                     4594](https://www.rfc-editor.org/rfc/rfc4594.html)

  Mapping DiffServ to IEEE 802.11                    [RFC
                                                     8325](https://www.rfc-editor.org/rfc/rfc8325.html)

  One-way transmission time                          [ITU-T G.114](https://www.itu.int/rec/T-REC-G.114)
  -------------------------------------------------------------------------------------------------------

## Measurement and monitoring

  ---------------------------------------------------------------------------------------------------------------
  Topic                                                      Reference
  ---------------------------------------------------------- ----------------------------------------------------
  Framework for TCP throughput testing                       [RFC
                                                             6349](https://www.rfc-editor.org/rfc/rfc6349.html)

  Benchmarking methodology for network devices               [RFC
                                                             2544](https://www.rfc-editor.org/rfc/rfc2544.html)

  **RFC 2544 on production networks considered harmful**     [RFC
                                                             6815](https://www.rfc-editor.org/rfc/rfc6815.html)

  IPFIX protocol specification                               [RFC
                                                             7011](https://www.rfc-editor.org/rfc/rfc7011.html)

  sFlow                                                      [RFC
                                                             3176](https://www.rfc-editor.org/rfc/rfc3176.html)

  Interfaces group MIB                                       [RFC
                                                             2863](https://www.rfc-editor.org/rfc/rfc2863.html)

  SNMP management frameworks                                 [RFC
                                                             3411](https://www.rfc-editor.org/rfc/rfc3411.html)

  SNMPv3 user-based security model                           [RFC
                                                             3414](https://www.rfc-editor.org/rfc/rfc3414.html)
  ---------------------------------------------------------------------------------------------------------------

**Read RFC 6815 before citing RFC 2544.** RFC 2544 methods are designed
to overload a device under test in order to measure its capacity, and
RFC 6815 states plainly that they belong in an isolated test
environment. Running them on a production network harms user traffic.
For live path measurement, use RFC 6349 instead.

## Wireless and CAPWAP

  -----------------------------------------------------------------------------------------------------------
  Topic                                               Reference
  --------------------------------------------------- -------------------------------------------------------
  Wireless LAN (802.11 family)                        [IEEE
                                                      802.11](https://standards.ieee.org/ieee/802.11/7028/)

  Port-based network access control                   [IEEE
                                                      802.1X](https://standards.ieee.org/ieee/802.1X/7345/)

  CAPWAP protocol specification                       [RFC 5415](https://www.rfc-editor.org/rfc/rfc5415.html)

  ITU-R Radio Regulations (ISM bands)                 [ITU-R](https://www.itu.int/pub/R-REG-RR)
  -----------------------------------------------------------------------------------------------------------

## Ethernet, switching and cabling

  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------
  Topic                                       Reference
  ------------------------------------------- -------------------------------------------------------------------------------------------------------------------------
  Ethernet                                    [IEEE 802.3](https://standards.ieee.org/ieee/802.3/10422/)

  1000BASE-T over Category 5 (interpretation) [IEEE 802.3ab
                                              interpretation](https://standards.ieee.org/wp-content/uploads/import/documents/interpretations/802.3ab-1999_interp.pdf)

  VLAN bridged networks                       [IEEE 802.1Q](https://standards.ieee.org/ieee/802.1Q/10323/)

  Spanning Tree                               [IEEE 802.1D](https://standards.ieee.org/ieee/802.1D/3268/)

  Link aggregation                            [IEEE 802.1AX](https://standards.ieee.org/ieee/802.1AX/7404/)

  Powering electronic equipment               [IEEE 1100](https://standards.ieee.org/ieee/1100/2237/)

  Generic cabling for customer premises       [ISO/IEC 11801](https://www.iso.org/standard/66182.html)

  Fibre optic connector cleanliness           [IEC 61300-3-35](https://webstore.iec.ch/publication/24071)

  Structured cabling standards                [TIA](https://tiaonline.org/)
  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Network automation and telemetry

  ----------------------------------------------------------------------------------------
  Topic                               Reference
  ----------------------------------- ----------------------------------------------------
  NETCONF                             [RFC
                                      6241](https://www.rfc-editor.org/rfc/rfc6241.html)

  RESTCONF                            [RFC
                                      8040](https://www.rfc-editor.org/rfc/rfc8040.html)

  YANG 1.1                            [RFC
                                      7950](https://www.rfc-editor.org/rfc/rfc7950.html)
  ----------------------------------------------------------------------------------------

## Email

  -----------------------------------------------------------------------------------------------------
  Topic                                            Reference
  ------------------------------------------------ ----------------------------------------------------
  SMTP                                             [RFC
                                                   5321](https://www.rfc-editor.org/rfc/rfc5321.html)

  Email greylisting                                [RFC
                                                   6647](https://www.rfc-editor.org/rfc/rfc6647.html)

  Sender Policy Framework                          [RFC
                                                   7208](https://www.rfc-editor.org/rfc/rfc7208.html)

  FTP                                              [RFC
                                                   959](https://www.rfc-editor.org/rfc/rfc959.html)

  FTP extensions for NAT                           [RFC
                                                   2428](https://www.rfc-editor.org/rfc/rfc2428.html)

  Securing FTP with TLS                            [RFC
                                                   4217](https://www.rfc-editor.org/rfc/rfc4217.html)
  -----------------------------------------------------------------------------------------------------

## Time

  ---------------------------------------------------------------------------------
  Topic                        Reference
  ---------------------------- ----------------------------------------------------
  NTPv4                        [RFC
                               5905](https://www.rfc-editor.org/rfc/rfc5905.html)

  ---------------------------------------------------------------------------------

## Operations, security and process frameworks

  -----------------------------------------------------------------------------------------------------------------
  Topic                                   Reference
  --------------------------------------- -------------------------------------------------------------------------
  ITIL 4 service management               [Axelos](https://www.axelos.com/certifications/itil-service-management)

  Site Reliability Engineering            [Google SRE Book](https://sre.google/sre-book/table-of-contents/)

  SRE practices                           [Google SRE Workbook](https://sre.google/workbook/table-of-contents/)

  Incident response                       [NIST SP 800-61 Rev. 3](https://csrc.nist.gov/pubs/sp/800/61/r3/final)

  Firewall policy guidelines              [NIST SP 800-41 Rev. 1](https://csrc.nist.gov/pubs/sp/800/41/r1/final)

  Digital identity guidelines             [NIST SP 800-63 Revision 4](https://pages.nist.gov/800-63-4/)

  Securing wireless LANs                  [NIST SP 800-153](https://csrc.nist.gov/pubs/sp/800/153/final)

  IoT device cybersecurity                [NIST SP 800-213](https://csrc.nist.gov/pubs/sp/800/213/final)

  Secure IPv6 deployment                  [NIST SP 800-119](https://csrc.nist.gov/pubs/sp/800/119/final)

  Adversary tactics and techniques        [MITRE ATT&CK](https://attack.mitre.org/)
  -----------------------------------------------------------------------------------------------------------------

**Note on NIST currency.** SP 800-61 Rev. 2 was withdrawn on 3 April
2025 and superseded by Rev. 3. The SP 800-63-3 family has been
superseded by Revision 4. If you are citing NIST in your own work, check
the publication page rather than a search result, because withdrawn
documents remain online and rank well.

## Vendor documentation

Vendor behaviour changes between releases far more often than standards
do, so treat these as current-state references rather than as settled
facts.

  --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  Topic                                     Reference
  ----------------------------------------- --------------------------------------------------------------------------------------------------------------------------------------
  AWS VPC                                   [docs.aws.amazon.com/vpc](https://docs.aws.amazon.com/vpc/)

  AWS EC2 instance IP addressing            [EC2 user guide](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/using-instance-addressing.html)

  AWS target group health checks            [ELB documentation](https://docs.aws.amazon.com/elasticloadbalancing/latest/application/target-group-health-checks.html)

  Windows domain profile detection          [Microsoft
                                            Learn](https://learn.microsoft.com/en-us/troubleshoot/windows-client/networking/domain-joined-machines-cannot-detect-domain-profile)

  Linux ip-route                            [man7.org](https://man7.org/linux/man-pages/man8/ip-route.8.html)

  SFF specifications (optics diagnostics)   [SNIA SFF](https://www.snia.org/technology-communities/sff/specifications)
  --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Lab platforms

Build the scenarios rather than only reading them.

  -------------------------------------------------------------------------------------------------------
  Platform                                                 Best for
  -------------------------------------------------------- ----------------------------------------------
  [Containerlab](https://containerlab.dev/)                Fast container-based topologies, modern NOS
                                                           images

  [GNS3](https://www.gns3.com/)                            Mixed vendor labs with real images

  [EVE-NG](https://www.eve-ng.net/)                        Larger multi-vendor topologies

  [Cisco Packet                                            Free, enough for the whole L1 path
  Tracer](https://www.netacad.com/courses/packet-tracer)   

  [Wireshark sample                                        Packet analysis practice without building
  captures](https://wiki.wireshark.org/SampleCaptures)     anything
  -------------------------------------------------------------------------------------------------------

# Appendix G. Research Foundations

The primary references in this book are standards: RFCs, IEEE documents,
NIST publications and vendor documentation. Standards tell you how a
protocol is supposed to behave. The peer-reviewed studies below measure
how networks actually behave in production, and several of them explain
*why* a scenario in this book is common. They are useful background for
L3 interviews, where "what is your evidence?" is a standard follow-up
question.

Each entry gives the full citation, a DOI link where one could be
verified, and the scenarios it supports. Two entries are given without a
DOI because none could be confirmed; they are cited by venue and page
range instead.

## Transport performance and path MTU

**\[G1\]** V. Jacobson, "Congestion avoidance and control," in
*Proceedings of ACM SIGCOMM '88*, Stanford, CA, USA, 1988, pp. 314--329.
DOI: https://doi.org/10.1145/52324.52356

The paper that introduced slow start, round-trip-time variance
estimation and TCP congestion avoidance, written in response to the
Internet congestion collapses of 1986. It is the origin of the TCP
behaviour behind throughput questions such as
[Q41](#q41.-a-remote-office-has-poor-vpn-performance-despite-a-good-local-speed-test),
[Q58](#q58.-bandwidth-graphs-show-a-steady-climb-toward-saturation-on-a-wan-link)
and
[Q95](#q95.-a-servers-throughput-is-capped-well-below-the-nics-rated-speed).

**\[G2\]** M. Mathis, J. Semke, J. Mahdavi and T. Ott, "The macroscopic
behavior of the TCP congestion avoidance algorithm," *ACM SIGCOMM
Computer Communication Review*, vol. 27, no. 3, pp. 67--82, 1997. DOI:
https://doi.org/10.1145/263932.264023

Derives and validates a model that predicts the bandwidth of a sustained
TCP connection under light to moderate loss. Throughput is proportional
to segment size and inversely proportional to round-trip time and to the
square root of the loss rate. This is the quantitative reason a fast
local speed test can coexist with a slow tunnel
([Q41](#q41.-a-remote-office-has-poor-vpn-performance-despite-a-good-local-speed-test)),
and why a single flow cannot fill a long-distance path
([Q71](#q71.-cross-region-cloud-traffic-has-unexpectedly-high-latency),
[Q95](#q95.-a-servers-throughput-is-capped-well-below-the-nics-rated-speed)).

**\[G3\]** M. Luckie and B. Stasiewicz, "Measuring path MTU discovery
behaviour," in *Proceedings of the 10th ACM Internet Measurement
Conference (IMC '10)*, Melbourne, Australia, 2010, pp. 102--108. DOI:
https://doi.org/10.1145/1879141.1879155

Measured path MTU discovery for 50,000 popular websites and found an
IPv4 failure rate of between 5 and 18 percent, depending on the MTU of
the constraining link. The authors also found that many failures were
caused by software bugs rather than by firewalls discarding ICMP.
Background for
[Q33](#q33.-users-can-browse-sites-but-file-downloads-consistently-fail-or-hang),
[Q37](#q37.-a-site-to-site-vpn-drops-whenever-large-file-transfers-start)
and
[Q106](#q106.-ipv6-connections-hang-on-large-transfers-while-small-requests-work),
and a useful caution against assuming every stalled transfer is a
filtered ICMP message.

## DNS and dual-stack behaviour

**\[G4\]** J. Jung, E. Sit, H. Balakrishnan and R. Morris, "DNS
performance and the effectiveness of caching," *IEEE/ACM Transactions on
Networking*, vol. 10, no. 5, pp. 589--603, 2002. DOI:
https://doi.org/10.1109/TNET.2002.803905

A measurement study of DNS lookup performance and of how effective
caching is in practice. Background for why caches and TTLs shape what
clients see after a change
([Q22](#q22.-after-a-dns-record-change-some-users-still-resolve-the-old-ip)),
and for resolver-path problems
([Q16](#q16.-internal-dns-resolves-fine-but-external-domains-fail-intermittently)).

**\[G5\]** V. Bajpai and J. Schönwälder, "Measuring the effects of Happy
Eyeballs," in *Proceedings of the 2016 Applied Networking Research
Workshop (ANRW '16)*, Berlin, Germany, 2016. DOI:
https://doi.org/10.1145/2959424.2959429

Used a three-year dataset from 80 dual-stacked measurement probes to
study how Happy Eyeballs chooses between IPv6 and IPv4. It found that
only around 1 percent of IPv6 connection times ever exceeded the 300 ms
timer then in use, so clients preferred IPv6 almost all of the time.
Background for
[Q102](#q102.-a-website-is-slow-to-load-for-some-users-but-fine-for-others-on-the-same-network)
and
[Q108](#q108.-a-hostname-returns-an-aaaa-record-but-the-service-is-unreachable).

**\[G6\]** J. Czyz, M. Luckie, M. Allman and M. Bailey, "Don't forget to
lock the back door! A characterization of IPv6 network security policy,"
in *Proceedings of the Network and Distributed System Security Symposium
(NDSS)*, San Diego, CA, USA, 2016. DOI:
https://doi.org/10.14722/ndss.2016.23047

A measurement of 520,000 dual-stack servers and 25,000 dual-stack
routers. It found services such as SSH, Telnet and SNMP more than twice
as open on routers over IPv6 as over IPv4. Every operator the authors
contacted confirmed that the difference was unintentional. This is the
research evidence behind
[Q107](#q107.-a-service-you-firewalled-off-is-still-reachable).

## Wireless

**\[G7\]** G. Bianchi, "Performance analysis of the IEEE 802.11
distributed coordination function," *IEEE Journal on Selected Areas in
Communications*, vol. 18, no. 3, pp. 535--547, 2000. DOI:
https://doi.org/10.1109/49.840210

The standard analytical model of 802.11 DCF throughput with a finite
number of contending stations. It formalises why wireless is a shared,
contended medium and why adding clients reduces what each one receives
([Q44](#q44.-wireless-throughput-is-much-lower-than-wired-for-the-same-user),
[Q75](#q75.-voip-quality-complaints-only-come-from-wireless-users-not-wired-ones)).

**\[G8\]** M. Heusse, F. Rousseau, G. Berger-Sabbatel and A. Duda,
"Performance anomaly of 802.11b," in *Proceedings of IEEE INFOCOM 2003*,
San Francisco, CA, USA, 2003, pp. 836--843. DOI:
https://doi.org/10.1109/INFCOM.2003.1208921

Showed that one host transmitting at 1 Mb/s can reduce the throughput of
hosts transmitting at 11 Mb/s to below 1 Mb/s, because CSMA/CA gives
every host equal access opportunity regardless of rate. This is the
mechanism behind disabling low legacy data rates in
[Q43](#q43.-a-new-ap-was-added-but-clients-still-connect-to-a-farther-weaker-ap)
and the airtime point in
[Q44](#q44.-wireless-throughput-is-much-lower-than-wired-for-the-same-user).

**\[G9\]** J. Martin, T. Mayberry, C. Donahue, L. Foppe, L. Brown, C.
Riggins, E. C. Rye and D. Brown, "A study of MAC address randomization
in mobile devices and when it fails," *Proceedings on Privacy Enhancing
Technologies*, vol. 2017, no. 4, pp. 365--383, 2017. DOI:
https://doi.org/10.1515/popets-2017-0054

The first wide-scale study of MAC address randomisation in the field,
broken down by operating system, manufacturer and model. It found
adoption and implementation varied widely between vendors. Background
for why client identity is unreliable in DHCP pools and on guest
networks
([Q18](#q18.-a-branch-office-dhcp-scope-is-exhausted-despite-low-headcount)).

## Security policy and configuration

**\[G10\]** A. Wool, "A quantitative study of firewall configuration
errors," *IEEE Computer*, vol. 37, no. 6, pp. 62--67, 2004. DOI:
<https://doi.org/10.1109/MC.2004.2>

Analysed real corporate firewall rule sets and found that they often
enforce policies violating well-established security guidelines, with
the number of errors rising with rule-set complexity. Background for
rule-order and review questions such as
[Q23](#q23.-traffic-is-allowed-by-an-acl-but-still-blocked) and
[Q32](#q32.-a-misconfigured-acl-blocked-a-critical-application-at-2-am).

## Failures, operations and availability

**\[G11\]** P. Gill, N. Jain and N. Nagappan, "Understanding network
failures in data centers: measurement, analysis, and implications," in
*Proceedings of ACM SIGCOMM 2011*, Toronto, Canada, 2011, pp. 350--361.
DOI: <https://doi.org/10.1145/2018436.2018477>

A large-scale study of failures across tens of data centres over more
than a year. Load balancers dominated failure occurrences, many of them
short-lived software faults, and network redundancy was only 40 percent
effective in reducing the median impact of a failure. Useful evidence
for
[Q14](#q14.-a-gateway-failover-didnt-happen-when-the-primary-router-failed)
(redundancy that does not take over),
[Q65](#q65.-a-load-balancer-keeps-sending-traffic-to-a-backend-server-thats-down)
(load balancer behaviour) and
[Q50](#q50.-monitoring-floods-with-hundreds-of-alerts-during-a-single-outage)
(correlating many alerts to one cause).

**\[G12\]** D. Turner, K. Levchenko, A. C. Snoeren and S. Savage,
"California fault lines: understanding the causes and impact of network
failures," in *Proceedings of ACM SIGCOMM 2010*, New Delhi, India, 2010.
No DOI verified; available from the first author's research page at the
University of California, San Diego.

Showed how a history of network failure events can be reconstructed by
mining "low-quality" data that networks already collect, such as syslog
and configuration records, rather than deploying new instrumentation.
Background for working from logs and counters in
[Q10](#q10.-interface-counters-show-high-input-errors-and-crc-errors),
[Q52](#q52.-a-flapping-interface-downup-alert-every-5-minutes-on-a-core-switch)
and
[Q57](#q57.-how-do-you-document-a-resolved-incident-for-future-reference).

**\[G13\]** R. Govindan, I. Minei, M. Kallahalla, B. Koley and A.
Vahdat, "Evolve or die: high-availability design principles drawn from
Google's network infrastructure," in *Proceedings of ACM SIGCOMM 2016*,
Florianópolis, Brazil, 2016. DOI:
https://doi.org/10.1145/2934872.2934891

An analysis of more than 100 high-impact failure events across Google's
data centres and two WANs. A large number of failures occurred while a
network management operation was in progress. The authors' design
principles include defence in depth, consistency across planes and
assessing root cause quickly. This is research support for the
change-control scenarios
[Q12](#q12.-a-default-route-was-removed-accidentally-and-internet-access-failed-network-wide),
[Q32](#q32.-a-misconfigured-acl-blocked-a-critical-application-at-2-am),
[Q62](#q62.-another-teams-change-caused-an-outage-and-the-noc-wasnt-told)
and
[Q64](#q64.-configuration-drift-is-causing-repeat-incidents-across-similar-devices),
and for [Chapter 10](#chapter-10.-escalation-itil-and-communication)
generally.

## Time

**\[G14\]** D. L. Mills, "Internet time synchronization: the Network
Time Protocol," *IEEE Transactions on Communications*, vol. 39, no. 10,
pp. 1482--1493, 1991. No DOI verified; cited by volume and page range.

The paper that brought the NTP architecture, protocol and algorithms to
the wider engineering community. It describes the hierarchical,
self-organising subnet of time servers that
[Q99](#q99.-ntp-sync-failures-are-causing-certificate-and-authentication-errors)
depends on.

# Appendix H. Glossary

Terms are defined as they are used in this book. Where a term has a
governing standard, it is listed in [Appendix
F](#appendix-f.-standards-index).

  ------------------------------------------------------------------------------------------------
  Term           Meaning
  -------------- ---------------------------------------------------------------------------------
  AAAA record    DNS record that maps a name to an IPv6 address

  AC_VO          The Wi-Fi Multimedia access category for voice, given the highest priority for
                 airtime

  ACK            Acknowledgement. In TCP, confirms received data; in SIP, confirms a final
                 response to an INVITE

  ACL            Access control list. An ordered set of permit and deny rules evaluated top to
                 bottom until the first match

  ALG            Application layer gateway. A firewall or NAT function that reads application
                 signalling, such as SIP or FTP, and rewrites addresses or opens pinholes

  APIPA          Automatic Private IP Addressing. A self-assigned IPv4 link-local address in
                 169.254.0.0/16, used when DHCP fails

  ARP            Address Resolution Protocol. Maps an IPv4 address to a MAC address on the local
                 link

  BFD            Bidirectional Forwarding Detection. A lightweight protocol that detects path
                 failure in milliseconds for routing and redundancy protocols

  BGP            Border Gateway Protocol. The path-vector routing protocol used between autonomous
                 systems

  Blast radius   The set of users, sites and services affected by a fault or a change

  BPDU           Bridge Protocol Data Unit. The frame spanning tree uses to elect a root and
                 detect loops

  CAB            Change Advisory Board. The group that reviews and approves changes

  CAPWAP         Control And Provisioning of Wireless Access Points. The protocol between
                 lightweight access points and a controller (UDP 5246 and 5247)

  CEF            Cisco Express Forwarding. The hardware or optimised software forwarding path that
                 keeps transit traffic off the CPU

  CIDR           Classless Inter-Domain Routing. Prefix notation such as 10.1.0.0/16

  Control plane  The part of a device that runs routing protocols and management, as distinct from
                 the data plane that forwards traffic

  CRC error      A frame whose checksum does not match its contents, meaning it was corrupted in
                 transit

  Dead peer      An IKE mechanism that detects when the far end of a tunnel has stopped responding
  detection      

  DF bit         The IPv4 "Don't Fragment" flag. Routers must drop an oversized packet with DF set
                 and should return ICMP Type 3 Code 4

  DHCP relay     A router function (for example `ip`` helper-address`) that forwards DHCP
                 broadcasts as unicast to a server on another subnet

  DSCP           Differentiated Services Code Point. The six-bit IP header field used to mark
                 traffic for QoS treatment. EF (46) is the usual voice marking

  ECMP           Equal-cost multipath. Load sharing across several routes of equal cost, usually
                 by hashing each flow onto one path

  EDNS0          Extension mechanisms for DNS that allow UDP responses larger than 512 bytes

  EtherChannel   Cisco's term for link aggregation. See LACP

  FHRP           First-hop redundancy protocol, such as HSRP, VRRP or GLBP, providing a shared
                 virtual default gateway

  Greylisting    An anti-spam technique that temporarily rejects mail from unknown senders,
                 relying on legitimate servers to retry

  Happy Eyeballs The client algorithm that races IPv6 and IPv4 connection attempts and uses
                 whichever succeeds first

  Health check   A probe a load balancer sends to decide whether a backend should receive traffic

  ICMPv6         ICMP for IPv6. It carries Neighbor Discovery and Packet Too Big messages and
                 cannot be blocked wholesale

  IKE            Internet Key Exchange. Negotiates IPsec security associations (UDP 500, and UDP
                 4500 with NAT traversal)

  IPsec          A suite that provides encryption and integrity for IP packets, using ESP in
                 almost all modern deployments

  Jitter         Variation in packet delay. Voice targets are usually under 30 ms

  LACP           Link Aggregation Control Protocol (IEEE 802.1AX). Bundles several physical links
                 into one logical link

  Link-local     An address valid only on the local link: 169.254.0.0/16 in IPv4, fe80::/10 in
  address        IPv6

  Longest prefix The rule that a router forwards using the most specific route that covers the
  match          destination

  MSS clamping   Rewriting the TCP maximum segment size during the handshake so segments fit a
                 smaller path MTU. It affects TCP only

  MTU            Maximum transmission unit. The largest packet a link carries without
                 fragmentation

  MTR            A tool that combines traceroute and continuous ping to show loss and latency per
                 hop

  NAC            Network access control. Admission based on authentication (usually 802.1X) and
                 often device posture

  NACL           Network ACL. In AWS, a stateless subnet-level filter that needs explicit rules
                 for return traffic

  NAT            Network Address Translation. Rewrites source or destination addresses, commonly
                 private to public

  Native VLAN    The VLAN whose frames cross an 802.1Q trunk untagged

  Neighbor       The IPv6 protocol, carried in ICMPv6, that replaces ARP and provides router and
  Discovery      prefix discovery

  NTP            Network Time Protocol. Synchronises clocks through a hierarchy of servers
                 identified by stratum

  OTDR           Optical time-domain reflectometer. Locates breaks, bends and bad splices on a
                 fibre by distance

  P1 to P4       Incident priority levels derived from business impact and urgency. P1 is a major
                 outage

  PMTUD          Path MTU discovery. The process by which a sender learns the smallest MTU on a
                 path from ICMP feedback

  PoE            Power over Ethernet. Supplies power to devices such as access points and phones
                 over the data cable

  PortFast       A switch port setting that moves an edge port straight to forwarding without
                 generating topology changes

  Posture        A NAC check that a device meets compliance rules, such as current antivirus
  assessment     definitions

  Problem        The ITIL practice that finds and removes the root cause of recurring incidents
  management     

  RA             Router Advertisement. The ICMPv6 message in which IPv6 routers announce prefixes
                 and themselves as gateways

  RA Guard       A switch feature that blocks Router Advertisements from ports that should not
                 send them

  RCA            Root cause analysis. The investigation, and the document, explaining why an
                 incident happened

  RDNSS          Recursive DNS Server option. Carries DNS server addresses inside an IPv6 Router
                 Advertisement

  Rollback       Returning a system to its state before a change. It is not always available or
                 safe, see
                 [Q90](#q90.-a-change-you-made-caused-unexpected-downtime.-whats-your-next-step)

  RSSI           Received signal strength indicator, in dBm. Voice designs usually target better
                 than -67 dBm

  RTP            Real-time Transport Protocol. Carries voice and video media, separately from
                 signalling

  Runbook        The documented procedure for handling a known scenario

  SA             Security association. A negotiated set of IPsec keys and parameters for one
                 direction of traffic

  SAN            Subject Alternative Name. The certificate field listing every hostname the
                 certificate is valid for

  SDP            Session Description Protocol. Describes media addresses, ports and codecs inside
                 SIP messages

  Security group In AWS, a stateful instance-level filter; allowing outbound traffic implicitly
                 allows its return

  SIP            Session Initiation Protocol. Sets up, modifies and tears down voice and video
                 calls

  SLA            Service level agreement. The contractual response and resolution times for
                 incidents

  SLAAC          Stateless Address Autoconfiguration. IPv6 hosts build their own addresses from an
                 advertised prefix

  SNI            Server Name Indication. The TLS extension that tells a shared server which
                 hostname the client wants

  SNMP           Simple Network Management Protocol. Used by monitoring systems to poll device
                 state (UDP 161, traps on UDP 162)

  SNR            Signal-to-noise ratio, in dB. Voice designs usually target 25 dB or better

  STAR           Situation, Task, Action, Result. A structure for answering behavioural interview
                 questions

  STP            Spanning Tree Protocol and its variants (RSTP, MSTP). Blocks redundant Layer 2
                 paths to prevent loops

  Stateful       Describes a device that tracks connections and permits return traffic
                 automatically

  Stratum        An NTP server's distance from a reference clock. Stratum 16 means unsynchronised

  SVI            Switched virtual interface. A routed Layer 3 interface for a VLAN on a multilayer
                 switch

  TCN            Topology Change Notification. A spanning tree message that shortens MAC table
                 ageing across the domain

  TTL            Time to live. In IP, a hop limit; in DNS, how long a cached answer may be used

  VLAN           Virtual LAN. A logical broadcast domain on a switched network

  VRF            Virtual routing and forwarding. Separate routing tables on one device

  WMM            Wi-Fi Multimedia. The 802.11e-based prioritisation of traffic into access
                 categories
  ------------------------------------------------------------------------------------------------

# Thank you for choosing this guide to prepare for your NOC Engineer interview. I continually strive to improve these resources and welcome your feedback; if you notice any errors or have suggestions, please reach out at contact@iteducationnepal.org or contact@jiwanbhattarai.com. For additional role-based IT interview guides, please visit iteducationnepal.org. Best of luck in your upcoming interviews and your continued career in IT.

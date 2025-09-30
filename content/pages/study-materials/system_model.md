---
content_type: page
description: ''
learning_resource_types: []
ocw_type: CourseSection
parent_title: Study Materials
parent_type: CourseSection
parent_uid: a7a8f9ef-1f9b-6ce1-6418-f519b9fd5b7a
title: System Model
uid: 57dd520a-3a29-4286-6357-2d8872899351
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

{{% resource_link 96318087-6dc8-d015-eabe-0265173b1d36 "Main" %}} | {{% resource_link 7772984a-0715-ec47-488a-c34f735f05c9 "Hardware" %}} | System Model | {{% resource_link 80cbfe73-1932-d102-278f-8a2130fc3b1e "Linearized Control" %}} | {{% resource_link 73744b95-66b8-8de0-1f15-daae37af3278 "Nonlinear Control" %}} | {{% resource_link a37c83c8-41e1-b04b-28e0-6d03e3f80462 "Movies" %}} | {{% resource_link bfdd131f-a0a4-3b0e-5c4d-8f39f6779574 "Technical Details" %}} | {{% resource_link 78238558-c617-c260-7a01-172fb0765a81 "Credits" %}}

The first step in controlling a system is deriving an accurate model for the system. Each of the system elements' behaviors can be derived from basic physics. In the examples below, many of the equations are left in terms of constants. These constants are dependent on materials and geometry, and are thus specific to the hardware. Procedures for measuring these constants are provided in Yi Xie's MEng thesis (see the {{% resource_link bfdd131f-a0a4-3b0e-5c4d-8f39f6779574 "technical details" %}} section).

{{< resource "1fed5bbc-9b58-0829-1f31-05931483a39f" >}}

Free Body Diagram of the Plant. (Fig. M1)

As shown in the free body diagram above, two forces act on the steel ball: gravity and the electro-magnetic force from the coils. The equation of motion for the ball is therefore:

{{< resource "701633de-ac79-7ac2-520b-49f7c38b3114" >}}

Eq. M1.

In the simplest model, F{{< sub "m" >}}, the electromagnetic force, is proportional to the square of the current passing through the inductor and inversely proportional to the square of the distance between the magnet and the steel ball. The constant C is a function of the physical construction of the electromagnet.

{{< resource "9669154c-4649-0247-72e1-e445249597a3" >}}

Eq. M2.

The power amplifier is set up as an actively controlled current source, so we assume current to be the controlled variable. This means that we can ignore coil inductance and speed voltage effects. Combining the two equations given above gives:

{{< resource "18d8d15e-d078-e595-ea7b-f45942af3124" >}}

Eq. M3.
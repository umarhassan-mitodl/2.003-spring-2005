---
content_type: page
description: ''
learning_resource_types: []
ocw_type: CourseSection
parent_title: Study Materials
parent_type: CourseSection
parent_uid: a7a8f9ef-1f9b-6ce1-6418-f519b9fd5b7a
title: Nonlinear Control
uid: 73744b95-66b8-8de0-1f15-daae37af3278
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

{{% resource_link 96318087-6dc8-d015-eabe-0265173b1d36 "Main" %}} | {{% resource_link 7772984a-0715-ec47-488a-c34f735f05c9 "Hardware" %}} | {{% resource_link 57dd520a-3a29-4286-6357-2d8872899351 "System Model" %}} | {{% resource_link 80cbfe73-1932-d102-278f-8a2130fc3b1e "Linearized Control" %}} | Nonlinear Control | {{% resource_link a37c83c8-41e1-b04b-28e0-6d03e3f80462 "Movies" %}} | {{% resource_link bfdd131f-a0a4-3b0e-5c4d-8f39f6779574 "Technical Details" %}} | {{% resource_link 78238558-c617-c260-7a01-172fb0765a81 "Credits" %}}

While linearizing the behavior of the plant and applying traditional linear control methods is an effective method of controlling the system, it is only effective around the chosen opperating point. Large deviations from this point lead to instabilities and the eventual failure of the system to remain in the desired position. Our demonstration maglev system operates over a wide range of positions, with gaps from about 5 to 15 mm. This span is too great for a linearized control system to handle, requiring a nonlinear control system.

The basics of our non-linear control system are as follows. The chief difference is that the nonlinear design has an extra nonlinear block between the linear controller and the plant. This extra element combines with the plant to form an effectively linear system, which is controlled in the traditional manner.

{{< resource "2add1483-86a2-cf83-3d4b-ae44178beffd" >}}

Fig. N1.

The inputs on the nonlinear block are the measured position of the ball and the force requested by the linear section of the control system. The computer sums the desired force and the constant gravitational force to produce the needed magnetic force:

{{< resource "a7a03e2c-a97c-e249-e812-92f0ab792e87" >}}

Eq. N1.

{{< resource "79c715d5-4d53-5f7b-efcf-46f9e8e9f522" >}}

Eq. N2.

{{< resource "f333e795-881d-e662-9786-94600cf7fd1d" >}}

Eq. N3.

Based on the magnetic force needed, the computer takes the measured distance of the ball from the magnet and calculates the current needed to supply that force at the given distance via

{{< resource "2e01bcd9-65fa-ed48-43ac-823a31d39b3b" >}}

Eq. N4.

Success in using this method of control is very dependent on having an accurate model of the system's behavior. The construction of such a model is demonstrated in Yi Xie's thesis, in the {{% resource_link bfdd131f-a0a4-3b0e-5c4d-8f39f6779574 "technical details" %}} section.
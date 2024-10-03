---
pagetitle: Release Notes for LSM6DSV16BX Component
lang: en
header-includes: <link rel="icon" type="image/x-icon" href="_htmresc/favicon.png" />
---

::: {.row}
::: {.col-sm-12 .col-lg-4}

<center>
# Release Notes for LSM6DSV16BX Component Driver
Copyright &copy; 2022 STMicroelectronics\

[![ST logo](_htmresc/st_logo_2020.png)](https://www.st.com){.logo}
</center>

# License

This software component is licensed by ST under BSD 3-Clause license, the "License".
You may not use this component except in compliance with the License. You may obtain a copy of the License at:

[BSD 3-Clause license](https://opensource.org/licenses/BSD-3-Clause)

# Purpose

This directory contains the LSM6DSV16BX component drivers.
:::

::: {.col-sm-12 .col-lg-8}
# Update history

::: {.collapse}
<input type="checkbox" id="collapse-section1" aria-hidden="true">
<label for="collapse-section1" aria-hidden="true">V1.0.0 / 03-Aug-2022</label>
<div>

## Main changes

### First release

- First official release [ref. DS v2.0]

##

</div>

<input type="checkbox" id="collapse-section2" aria-hidden="true">
<label for="collapse-section2" aria-hidden="true">V2.0.0 / 16-Dic-2022</label>
<div>

## Main changes

- New release [ref. DS v3.0]

##

</div>

<input type="checkbox" id="collapse-section3" aria-hidden="true">
<label for="collapse-section3" aria-hidden="true">V2.1.0 / 01-June-2023</label>
<div>

## Main changes

- Add __weak directive to read/write registers routines
- Fix LSM6DSV16BX_MLC_ON_BEFORE_FSM usage and APIs

##

</div>

<input type="checkbox" id="collapse-section4" aria-hidden="true">
<label for="collapse-section4" aria-hidden="true">V2.1.1 / 25-July-2023</label>
<div>

## Main changes

- Fix gyro FS 4000dps value typo error

##

</div>

<input type="checkbox" id="collapse-section5" aria-hidden="true">
<label for="collapse-section5" aria-hidden="true">V2.1.2 / 25-July-2023</label>
<div>

## Main changes

- ah_qvar: Add API to convert from LSB to mV

##

</div>

<input type="checkbox" id="collapse-section6" aria-hidden="true">
<label for="collapse-section6" aria-hidden="true">V2.2.0 / 09-Nov-2023</label>
<div>

## Main changes

- Remove fsm_permission_status() API duplication
- Fix xl_mode_t and gy_mode_t enumeration values

##

</div>

<input type="checkbox" id="collapse-section7" aria-hidden="true">
<label for="collapse-section7" aria-hidden="true">V3.0.0 / 20-Mar-2024</label>
<div>

## Main changes

- Fixed code style (Artistic Style Version 3.4.13)
- Add "const" to ctx arg for all APIs

##

</div>

<input type="checkbox" id="collapse-section8" aria-hidden="true">
<label for="collapse-section8" aria-hidden="true">V3.1.0 / 28-Mar-2024</label>
<div>

## Main changes

- updated README.md file with tag reference and mdelay description
- Simplify few functions comment for readability
- Fix typo on lsm6dsv16bx_xl_offset_mg_t struct name
- Added xl_dualc_batch_from_if bit (DS Rev3)

##

</div>

<input type="checkbox" id="collapse-section9" aria-hidden="true">
<label for="collapse-section9" aria-hidden="true">V4.0.0 / 17-Apr-2024</label>
<div>

## Main changes

- Rename xl_axis_set/get routines adding 'tdm'
- Fixed few comments style and content
- Remove usage of eis/ois from driver

##

</div>

<input type="checkbox" id="collapse-section10" aria-hidden="true">
<label for="collapse-section10" aria-hidden="true">V4.1.0 / 03-May-2024</label>
<div>

## Main changes

- add ah_qvar interrupt/event handling
- Fix BDR counter regsters get/set APIs
- unify pin_int1_route and pin_int2_route struct

##

</div>

<input type="checkbox" id="collapse-section11" aria-hidden="true">
<label for="collapse-section11" aria-hidden="true">V5.0.0 / 23-Jun-2024</label>
<div>

## Main changes

- Add defs for num_phy routines

##

</div>

<input type="checkbox" id="collapse-section12" checked aria-hidden="true">
<label for="collapse-section12" aria-hidden="true">V5.0.1 / 03-Oct-2024</label>
<div>

## Main changes

- Fix mlc_out_get API

##

</div>
:::


:::
:::

<footer class="sticky">
::: {.columns}
::: {.column width="95%"}
For complete documentation on LSM6DSV16BX,
visit:
[LSM6DSV16BX](https://www.st.com/content/st_com/en/products/mems-and-sensors/inemo-inertial-modules/lsm6dsv16bx.html)
:::
::: {.column width="5%"}
<abbr title="Based on template cx566953 version 2.0">Info</abbr>
:::
:::
</footer>

# Separate Quotation and Sale Order Numbers

![Odoo](https://img.shields.io/badge/Odoo-17.0-714B67) ![Editions](https://img.shields.io/badge/Editions-Community%2C_Enterprise-2563EB) ![License](https://img.shields.io/badge/License-LGPL--3-0F766E)

Auditors and sales managers often want quotations and confirmed orders numbered in separate series. This app gives each quotation a number from one sequence and assigns a second number from another sequence when the order is confirmed.

## What it does

- Quotation Name from its own sequence when the quotation is created
- Sale Order Name from a second sequence on confirmation
- Both sequences editable under Settings, Technical, Sequences

## How to use it

1. Install the app and create a quotation. Confirm it to see the second number.

## Technical notes

Technical name `sale_sequence`, Odoo 17.0.

Overrides `create` and `write` on `sale.order` and ships two `ir.sequence` records. Depends on `sale`.

## Get the module

This module is not on the Odoo App Store yet. Email [iusmanghias@gmail.com](mailto:iusmanghias@gmail.com?subject=sale_sequence) for a licence, the full source code and installation on your database.

Need it on another Odoo version, with changes for your workflow, or installed and tested on Odoo.sh? Email [iusmanghias@gmail.com](mailto:iusmanghias@gmail.com?subject=sale_sequence%20customisation) or see [CODCrafters](https://codcrafters.org).

---

This repository is the product page. The module source is private and comes with the licence.

Built by [Usman Ghias](https://usmanghias.co.uk), [CODCrafters](https://codcrafters.org).

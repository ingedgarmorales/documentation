=============================
Assign leads based on scoring
=============================

With *Lead Scoring* you can automatically rank your leads based on
selected criteria.

For example, you could score customers higher from your country higher or for
visiting specific pages on your website.

Configuration
=============

To use scoring, install the free module *Lead Scoring* under your
*Apps* page (only available in Odoo Enterprise).

.. image:: media/lead_scoring01.png
   :align: center

Create scoring rules
====================

You now have a new tab in your *CRM* app called *Leads*
where you can manage your scoring rules.

Here's an example of a Canadian lead. You can modify your rules for whatever
criteria you want to score leads on. You can add as many criteria
as you would like.

.. image:: media/lead_scoring02.png
   :align: center

Every lead without a score will automatically be scanned every hour and
assigned the correct score according to your configured scoring rules.

.. image:: media/lead_scoring03.png
   :align: center

Assign leads
============

Once the score is computed, leads can be assigned to specific teams using
the same domain mechanism. To do so go to :menuselection:`CRM --> Leads --> Team Assignment`
and apply a specific domain to each team. This domain can include scores.

.. image:: media/lead_scoring04.png
   :align: center

If you want more granularity, you can assign leads to a specific salesperson on the team using
further refined domains.

To do so go to :menuselection:`CRM --> Leads --> Leads Assignment`.

.. image:: media/lead_scoring05.png
   :align: center

.. note::
   The team & leads assignments will assign the unassigned leads
   once per day.

Evaluate & use the unassigned leads
===================================

Once your scoring rules are in place, you likely will still have
some unassigned leads. Some of these leads could still transition into an opportunity, so
ensuring they are handled is both useful and important.

On your leads overview page, you filter for your unassigned leads.

.. image:: media/lead_scoring06.png
   :align: center

You can also easily find unassigned leads by using the :menuselection:`Email Marketing` or
:menuselection:`Marketing Automation` apps to create a re-engagement campaign.

.. image:: media/lead_scoring07.png
   :align: center

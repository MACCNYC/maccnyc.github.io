---
title: Support MACC
permalink: "/donate"
layout: simple-page
---

{% t donate.Monetary_support %}

## {% t donate.One_time_support %}

<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
<input type="hidden" name="cmd" value="_s-xclick">
<input type="hidden" name="hosted_button_id" value="H6RL4XCPSLHKW">
<input type="image" src="{% t donate.donate_button %}" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!">
<img alt="" border="0" src="https://www.paypalobjects.com/en_US/i/scr/pixel.gif" width="1" height="1">
</form>

## {% t donate.Monthly_support %}

<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
<select name="os0">
    <option value="$5 Donation">{% t donate.Monthly_donation %}: $5 USD</option>
    <option value="$10 Donation">{% t donate.Monthly_donation %}: $10 USD</option>
    <option value="$15 Donation">{% t donate.Monthly_donation %}: $15 USD</option>
    <option value="$20 Donation">{% t donate.Monthly_donation %}: $20 USD</option>
    <option value="$25 Donation">{% t donate.Monthly_donation %}: $25 USD</option>
    <option value="$30 Donation">{% t donate.Monthly_donation %}: $30 USD</option>
    <option value="$35 Donation">{% t donate.Monthly_donation %}: $35 USD</option>
    <option value="$40 Donation">{% t donate.Monthly_donation %}: $40 USD</option>
    <option value="$45 Donation">{% t donate.Monthly_donation %}: $45 USD</option>
    <option value="$50 Donation">{% t donate.Monthly_donation %}: $50 USD</option>
</select>
<br/><br/>
<input type="image" src="{% t donate.subscribe_button %}" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!">
<input type="hidden" name="cmd" value="_s-xclick">
<input type="hidden" name="hosted_button_id" value="U2UPMHXPUJT6J">
<input type="hidden" name="on0" value="Donation Subscription Options">
<input type="hidden" name="on1" value="Monthly Subscription Donation">
<input type="hidden" name="currency_code" value="USD">
<img alt="" border="0" src="https://www.paypalobjects.com/en_US/i/scr/pixel.gif" width="1" height="1">
</form>

{% t donate.or_click_above %}

## [{% t donate.Pledge_to_bail_fund %}](http://www.macclegalfund.org)
{% t donate.bail_fund_explanation %}

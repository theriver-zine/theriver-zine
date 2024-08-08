---
layout: post
title: "{{ title }}"
author: "{{ author }}"
categories: "{{ category }}"
---

<table>
  <tr>
    <td style="padding-right: 20px;"><strong>What have you been reading recently?</strong></td>
    <td>{{ book_title }}, by {{ book_author }}</td>
  </tr>
  <tr><td colspan="2">&nbsp;</td></tr> <!-- Blank line -->

  <tr>
    <td style="padding-right: 20px;"><strong>What is it about?</strong></td>
    <td>{{ book_description }}</td>
  </tr>
  <tr><td colspan="2">&nbsp;</td></tr> <!-- Blank line -->

  <tr>
    <td style="padding-right: 20px;"><strong>How was it?</strong></td>
    <td>{{ book_review }}</td>
  </tr>
  <tr><td colspan="2">&nbsp;</td></tr> <!-- Blank line -->

  <tr>
    <td style="padding-right: 20px;"><strong>What stood out for you?</strong></td>
    <td>{{ standout_moments }}</td>
  </tr>
  <tr><td colspan="2">&nbsp;</td></tr> <!-- Blank line -->

  <tr>
    <td style="padding-right: 20px;"><strong>Who would you recommend it to?</strong></td>
    <td>{{ recommendation }}</td>
  </tr>
</table>
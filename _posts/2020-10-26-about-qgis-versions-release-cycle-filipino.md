---
layout: post
title: "Ukol sa mga bersyon at release cycle ng QGIS"
description: Ang post na ito ay naglalayong sagutin ang ilang katanungan ukol sa mga bersyon ng QGIS at ang kanyang release cycle. LTR, LR, ano nga ba ang mga ito? Bakit kaya kakadownload ko pa lang ng isang bersyon ng QGIS ay may bago na naman?
tags: [foss4g, qgis, qgis3, release cycle, filipino]
pinned: false
comments: true
og_type: article
image:
    facebook: /img/posts/2020-10-26-about-qgis-versions-release-cycle/main.png
    twitter: /img/posts/2020-10-26-about-qgis-versions-release-cycle/main.png
---

Ang post na ito ay naglalayong sagutin ang ilang katangungan ukol sa mga bersyon ng QGIS at ang release cycle nito. 

Una sa lahat, maari mong malaman ang version ng QGIS na gamit mo at iba pang impormasyon sa pamamagitan ng **Help -> Check QGIS Version** mula sa Menu bar.

## Mayroon bang schedule na sinusunod ang QGIS sa paglalabas ng bagong bersyon?
**Mayroon.** Ang release at development ng QGIS ay sumusunod sa isang timebased schedule or roadmap. Ang schedule o roadmap na nito ay maaring [makita dito](https://www.qgis.org/en/site/getinvolved/development/roadmap.html) o sa ibaba.

<table style="border:none">
<colgroup>
<col style="width: 18%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 15%" />
<col style="width: 18%" />
<col style="width: 7%" />
<col style="width: 9%" />
</colgroup>
<thead>
<tr class="row-odd"><th class="head"><p>Event</p></th>
<th class="head"><p>Latest</p></th>
<th class="head"><p>Long-Term
Repo</p></th>
<th class="head"><p>Freeze</p></th>
<th class="head"><p>Date</p></th>
<th class="head"><p>Week
#</p></th>
<th class="head"><p>Weeks</p></th>
</tr>
</thead>
<tbody>
<tr class="row-even"><td><p><strong>LTR</strong>/PR</p></td>
<td><p>3.4.0</p></td>
<td><p>2.18.25</p></td>
<td></td>
<td><p>2018-10-26</p></td>
<td><p>43</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-odd"><td><p>EPR</p></td>
<td><p>3.4.1</p></td>
<td></td>
<td></td>
<td><p>2018-11-02</p></td>
<td><p>44</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-even"><td><p>PR</p></td>
<td><p>3.4.2</p></td>
<td><p>2.18.26</p></td>
<td></td>
<td><p>2018-11-23</p></td>
<td><p>47</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-odd"><td><p>PR</p></td>
<td><p>3.4.3</p></td>
<td><p>2.18.27</p></td>
<td></td>
<td><p>2018-12-21</p></td>
<td><p>51</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-even"><td><p>PR/FF</p></td>
<td><p>3.4.4</p></td>
<td><p>2.18.28</p></td>
<td><p>3.5</p></td>
<td><p>2019-01-18</p></td>
<td><p>3</p></td>
<td><p>5</p></td>
</tr>
<tr class="row-odd"><td><p><strong>LR</strong>/PR</p></td>
<td><p>3.6.0</p></td>
<td><p>3.4.5</p></td>
<td></td>
<td><p>2019-02-22</p></td>
<td><p>8</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-even"><td><p>PR</p></td>
<td><p>3.6.1</p></td>
<td><p>3.4.6</p></td>
<td></td>
<td><p>2019-03-22</p></td>
<td><p>12</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-odd"><td><p>PR</p></td>
<td><p>3.6.2</p></td>
<td><p>3.4.7</p></td>
<td></td>
<td><p>2019-04-19</p></td>
<td><p>16</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-even"><td><p>PR/FF</p></td>
<td><p>3.6.3</p></td>
<td><p>3.4.8</p></td>
<td><p>3.7</p></td>
<td><p>2019-05-17</p></td>
<td><p>20</p></td>
<td><p>5</p></td>
</tr>
<tr class="row-odd"><td><p><strong>LR</strong>/PR</p></td>
<td><p>3.8.0</p></td>
<td><p>3.4.9</p></td>
<td></td>
<td><p>2019-06-21</p></td>
<td><p>25</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-even"><td><p>PR</p></td>
<td><p>3.8.1</p></td>
<td><p>3.4.10</p></td>
<td></td>
<td><p>2019-07-19</p></td>
<td><p>29</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-odd"><td><p>PR</p></td>
<td><p>3.8.2</p></td>
<td><p>3.4.11</p></td>
<td></td>
<td><p>2019-08-16</p></td>
<td><p>33</p></td>
<td><p>3</p></td>
</tr>
<tr class="row-even"><td><p>FF</p></td>
<td></td>
<td></td>
<td><p>3.9</p></td>
<td><p>2019-09-06</p></td>
<td><p>36</p></td>
<td><p>1</p></td>
</tr>
<tr class="row-odd"><td><p>PR</p></td>
<td><p>3.8.3</p></td>
<td><p>3.4.12</p></td>
<td></td>
<td><p>2019-09-13</p></td>
<td><p>37</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-even"><td><p>HF</p></td>
<td></td>
<td></td>
<td></td>
<td><p>2019-10-11</p></td>
<td><p>41</p></td>
<td><p>2</p></td>
</tr>
<tr class="row-odd"><td><p><strong>LTR</strong>/PR</p></td>
<td><p>3.10.0</p></td>
<td><p>3.4.13</p></td>
<td></td>
<td><p>2019-10-25</p></td>
<td><p>43</p></td>
<td><p>6</p></td>
</tr>
<tr class="row-even"><td><p>PR</p></td>
<td><p>3.10.1</p></td>
<td><p>3.4.14</p></td>
<td></td>
<td><p>2019-12-06</p></td>
<td><p>49</p></td>
<td><p>6</p></td>
</tr>
<tr class="row-odd"><td><p>PR/FF</p></td>
<td><p>3.10.2</p></td>
<td><p>3.4.15</p></td>
<td><p>3.11</p></td>
<td><p>2020-01-17</p></td>
<td><p>3</p></td>
<td><p>5</p></td>
</tr>
<tr class="row-even"><td><p><strong>LR</strong>/PR</p></td>
<td><p>3.12.0</p></td>
<td><p>3.10.3</p></td>
<td></td>
<td><p>2020-02-21</p></td>
<td><p>8</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-odd"><td><p>PR</p></td>
<td><p>3.12.1</p></td>
<td><p>3.10.4</p></td>
<td></td>
<td><p>2020-03-20</p></td>
<td><p>12</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-even"><td><p>PR</p></td>
<td><p>3.12.2</p></td>
<td><p>3.10.5</p></td>
<td></td>
<td><p>2020-04-17</p></td>
<td><p>16</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-odd"><td><p>PR/FF</p></td>
<td><p>3.12.3</p></td>
<td><p>3.10.6</p></td>
<td><p>3.13</p></td>
<td><p>2020-05-15</p></td>
<td><p>20</p></td>
<td><p>5</p></td>
</tr>
<tr class="row-even"><td><p><strong>LR</strong>/PR</p></td>
<td><p>3.14.0</p></td>
<td><p>3.10.7</p></td>
<td></td>
<td><p>2020-06-19</p></td>
<td><p>25</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-odd"><td><p>PR</p></td>
<td><p>3.14.1</p></td>
<td><p>3.10.8</p></td>
<td></td>
<td><p>2020-07-19</p></td>
<td><p>29</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-even"><td><p>PR</p></td>
<td><p>3.14.15</p></td>
<td><p>3.10.9</p></td>
<td></td>
<td><p>2020-08-14</p></td>
<td><p>33</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-odd"><td><p>PR/FF</p></td>
<td><p>3.14.16</p></td>
<td><p>3.10.10</p></td>
<td><p>3.15</p></td>
<td><p>2020-09-11</p></td>
<td><p>37</p></td>
<td><p>6</p></td>
</tr>
<tr class="row-even"><td><p><strong>LTR</strong>/PR</p></td>
<td><p>3.16.0</p></td>
<td><p>3.10.11</p></td>
<td></td>
<td><p>2020-10-23</p></td>
<td><p>43</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-odd"><td><p>PR</p></td>
<td><p>3.16.1</p></td>
<td><p>3.10.12</p></td>
<td></td>
<td><p>2020-11-20</p></td>
<td><p>47</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-even"><td><p>PR</p></td>
<td><p>3.16.2</p></td>
<td><p>3.10.13</p></td>
<td></td>
<td><p>2020-12-21</p></td>
<td><p>52</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-odd"><td><p>PR/FF</p></td>
<td><p>3.16.3</p></td>
<td><p>3.10.14</p></td>
<td><p>3.17</p></td>
<td><p>2021-01-15</p></td>
<td><p>3</p></td>
<td><p>5</p></td>
</tr>
<tr class="row-even"><td><p><strong>LR</strong>/PR</p></td>
<td><p>3.18.0</p></td>
<td><p>3.16.4</p></td>
<td></td>
<td><p>2021-02-19</p></td>
<td><p>8</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-odd"><td><p>PR</p></td>
<td><p>3.18.1</p></td>
<td><p>3.16.5</p></td>
<td></td>
<td><p>2021-03-19</p></td>
<td><p>12</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-even"><td><p>PR</p></td>
<td><p>3.18.2</p></td>
<td><p>3.16.6</p></td>
<td></td>
<td><p>2021-04-16</p></td>
<td><p>16</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-odd"><td><p>PR/FF</p></td>
<td><p>3.18.3</p></td>
<td><p>3.16.7</p></td>
<td><p>3.19</p></td>
<td><p>2021-05-14</p></td>
<td><p>20</p></td>
<td><p>5</p></td>
</tr>
<tr class="row-even"><td><p><strong>LR</strong>/PR</p></td>
<td><p>3.20.0</p></td>
<td><p>3.16.8</p></td>
<td></td>
<td><p>2021-06-18</p></td>
<td><p>25</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-odd"><td><p>PR</p></td>
<td><p>3.20.1</p></td>
<td><p>3.16.9</p></td>
<td></td>
<td><p>2021-07-16</p></td>
<td><p>29</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-even"><td><p>PR</p></td>
<td><p>3.20.2</p></td>
<td><p>3.16.10</p></td>
<td></td>
<td><p>2021-08-13</p></td>
<td><p>33</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-odd"><td><p>PR/FF</p></td>
<td><p>3.20.3</p></td>
<td><p>3.16.11</p></td>
<td><p>3.21</p></td>
<td><p>2021-09-10</p></td>
<td><p>37</p></td>
<td><p>6</p></td>
</tr>
<tr class="row-even"><td><p><strong>LTR</strong>/PR</p></td>
<td><p>3.22.0</p></td>
<td><p>3.16.12</p></td>
<td></td>
<td><p>2021-10-22</p></td>
<td><p>43</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-odd"><td><p>PR</p></td>
<td><p>3.22.1</p></td>
<td><p>3.16.13</p></td>
<td></td>
<td><p>2021-11-19</p></td>
<td><p>47</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-even"><td><p>PR</p></td>
<td><p>3.22.2</p></td>
<td><p>3.16.14</p></td>
<td></td>
<td><p>2021-12-17</p></td>
<td><p>51</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-odd"><td><p>PR/FF</p></td>
<td><p>3.22.3</p></td>
<td><p>3.16.15</p></td>
<td><p>3.23</p></td>
<td><p>2022-01-14</p></td>
<td><p>3</p></td>
<td><p>5</p></td>
</tr>
<tr class="row-even"><td><p><strong>LR</strong>/PR</p></td>
<td><p>3.24.0</p></td>
<td><p>3.22.4</p></td>
<td></td>
<td><p>2022-02-18</p></td>
<td><p>8</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-odd"><td><p>PR</p></td>
<td><p>3.24.1</p></td>
<td><p>3.22.5</p></td>
<td></td>
<td><p>2022-03-18</p></td>
<td><p>12</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-even"><td><p>PR</p></td>
<td><p>3.24.2</p></td>
<td><p>3.22.6</p></td>
<td></td>
<td><p>2022-04-15</p></td>
<td><p>16</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-odd"><td><p>PR/FF</p></td>
<td><p>3.24.3</p></td>
<td><p>3.22.7</p></td>
<td><p>3.25</p></td>
<td><p>2022-05-13</p></td>
<td><p>20</p></td>
<td><p>5</p></td>
</tr>
<tr class="row-even"><td><p><strong>LR</strong>/PR</p></td>
<td><p>3.26.0</p></td>
<td><p>3.22.8</p></td>
<td></td>
<td><p>2022-06-17</p></td>
<td><p>25</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-odd"><td><p>PR</p></td>
<td><p>3.26.1</p></td>
<td><p>3.22.9</p></td>
<td></td>
<td><p>2022-07-15</p></td>
<td><p>29</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-even"><td><p>PR</p></td>
<td><p>3.26.2</p></td>
<td><p>3.22.10</p></td>
<td></td>
<td><p>2022-08-12</p></td>
<td><p>33</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-odd"><td><p>PR/FF</p></td>
<td><p>3.26.3</p></td>
<td><p>3.22.11</p></td>
<td><p>3.27</p></td>
<td><p>2022-09-09</p></td>
<td><p>37</p></td>
<td><p>6</p></td>
</tr>
<tr class="row-even"><td><p><strong>LTR</strong>/PR</p></td>
<td><p>3.28.0</p></td>
<td><p>3.22.12</p></td>
<td></td>
<td><p>2022-10-21</p></td>
<td><p>43</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-odd"><td><p>PR</p></td>
<td><p>3.28.1</p></td>
<td><p>3.22.13</p></td>
<td></td>
<td><p>2022-11-18</p></td>
<td><p>47</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-even"><td><p>PR</p></td>
<td><p>3.28.2</p></td>
<td><p>3.22.14</p></td>
<td></td>
<td><p>2022-12-16</p></td>
<td><p>51</p></td>
<td><p>4</p></td>
</tr>
<tr class="row-odd"><td><p>PR/FF</p></td>
<td><p>3.28.3</p></td>
<td><p>3.22.15</p></td>
<td><p>3.29</p></td>
<td><p>2023-01-13</p></td>
<td><p>3</p></td>
<td><p>5</p></td>
</tr>
</tbody>
</table>

<br>
**Event Legend**
<table style="border: none">
<colgroup>
<col width="15%" />
<col width="85%" />
</colgroup>
<thead valign="bottom">
<tr class="row-odd"><th class="head">Event</th>
<th class="head">Description</th>
</tr>
</thead>
<tbody valign="top">
<tr class="row-even"><td>LTR</td>
<td>Long term release, begin of new development phase</td>
</tr>
<tr class="row-odd"><td>LR</td>
<td>Regular release, begin of new development phase</td>
</tr>
<tr class="row-even"><td>FF</td>
<td>Feature freeze, end of development phase</td>
</tr>
<tr class="row-odd"><td>HF</td>
<td>Hard freeze</td>
</tr>
<tr class="row-even"><td>SF</td>
<td>Soft freeze with bi-monthly vote</td>
</tr>
<tr class="row-odd"><td>PR</td>
<td>Point release of latest release and LTR branch</td>
</tr>
<tr class="row-even"><td>EPR</td>
<td>Extra Point release</td>
</tr>
</tbody>
</table>
<br>


## Ano ang ibig sabihin ng mga numero sa bersyon ng QGIS?
Makikita natin na ang bawat bersyon ng QGIS ay may kaakibat na tatlong numero (**X, Y, Z**). Halimbawa, **QGIS 3.10.11**. Ano nga ba ang ibig sabihin ng 3, 10, at 11?

Ang **X** ay ang **main version** ng QGIS. Sa ngayon, tayo ay nasa QGIS 3 na. Kaya ang mga release ng QGIS ay nagsisimula sa QGIS 3.

Ang **Y** ay kung anong **release version** ito. Ang release version ay sinisimbulo ng isang even number. Halimbawa: 3.2, 3.4, 3.6, 3.8, 3.12, 3.14, 3.16, 3.18, etc. Bakit nga ba sila even numbers? Ito ay dahil ang odd numbers ay nakareserba para sa development versions o yung mga bersyon kung saan nagaganap ang development ng QGIS bago sila i-release. Halimbawa: ang QGIS 3.1 ay ang development version para sa QGIS 3.2, ang QGIS 3.3 ay ang development version para sa QGIS 3.4.

Ang **Z** ay sumisimbulo kung pang-ilang Point Release (PR) na ito sa release version.

Bumalik tayo sa QGIS 3.10.11, ang ibig sabihin ng mga numerong ito ay:
- Ito ay base sa QGIS 3
- Ito ay base sa 3.10 release version
- Ito ang ika-labing-isa (11th) point release sa 3.10 version


## Ilang branches ba mayroon ang QGIS?
Technically, mayroong tatlong branches ang QGIS na maari mong idownload/install. Ito ay ang **Long Term Release (LTR) branch**, **Latest Release (LR) branch**, at ang **Development (Nightly) branch**. Bilang isang user, madalas ang mahalagang branches lang na kailangan natin ay ang LTR at LR branch. Ang development o nightly branch ay ang bersyon ng QGIS na nakabase sa pinakabagong bersyon ng source code ng QGIS at hindi ganun kasigurado ang stability nito ngunit kung nais mong ma-test o makita ang mga paparating na features ng QGIS, sa development o nightly branch mo sila mahahanap.


## Ano ang ibig sabihin ng LTR, LR, at PR?
Ang LTR, LR ay designations kung anong uri ng release ang bersyon na iyon. Tulad ng nabanggit sa itaas may LTR at LR branches (o bersyon) ng QGIS na maari nating i-install.

Ang **Long Term Release (LTR)** ay tinatawag na ganito sapagkat ito ay maintained at nakakatangap ng bug-fixes hanggang ilabas ang susunod na LTR. Sa ngayon, pinag-uusapan pa kung itataas ang length of support para sa LTR branch sa dalawang (2) taon mula sa kasalukuyang (1) taon. Sa kasalukuyan, ang LTR ay 3.10.11 subalit ito ay mapapalitan ng 3.16.4 sa Pebrero 2021.

Ang **Latest Release (LR)** ay ang release version ng QGIS na naglalaman ng mga pinakabagong featues nito. May bagong LR na inilalabas bawat apat na buwant. Halimbawa, ang 3.16 LR ay inilabas ngayong buwan ng Oktubre, ang susunod na LR (3.18) ay ilalabas apat na buwan mula ngayon sa Pebrero. Sa kasalukuyan, ang bawat ika-tatlong LR ay ang nagiging susunod na LTR. Halimbawa, ang LTR ngayon ay ang 3.10 release. Ang ikatlong release mula sa 3.10 ay 3.16 (3.10, 3.12, 3.14, 3.16) kaya ang susunod na LTR ay nakabase sa 3.16 release version.

Sa unang apat na buwan matapos ang release ng bagong designated LTR (3.16.0), hindi nito agad pinapalitan ang nakaraan LTR sa LTR repositories. Papalitan niya lamang ito kapag nailabas na din ang bagong LR (3.18.0).


## Ano naman ang nightly o development version?
Ang development o nightly na bersyon ay nakabase sa pinaka-recent na bersyon ng source code ng QGIS (master branch). Ang source code na ito ay maaring makita [dito](https://github.com/qgis/QGIS).

- Ang bersyon na ito ang may pinaka-bagong mga features (bleeding-edge) subalit karamihan sa kanila ay hindi pa natetest ng lubusan kaya maaring mayroon pa ding mga bugs.
- The best ang bersyon na ito kung gusto mong i-test ang mga nasabing bagong features.
- Hindi recommended ang bersyon na ito para sa production use o kung kailangan mo ng stable working environment.


## Ano ang development cycle ng QGIS at kailan sila nagrerelease ng mga bagong bersyon?
Tulad nga ng makikita sa itaas, consistent ang development cycle ng QGIS. Narito ang ilang bagay na kailangan mong malaman.
* Kada apat (4) na buwan ay may bagong release version na nilalabas.
* Sa apat na buwan na ito, ang unang tatlong (3) buwan ay nakalaan para sa development ng mga bagong features pati na rin sa pag-aayos ng mga bugs. Sa huling buwan ng release cycle, nagkakaroon ng tinatawag na feature freeze kung saan wala nang bagong developments or features at magsisimula ng magfocus sa testing, bug-fixing, translations, at paghahanda para sa release.
* Subalit, kada buwan ay naglalabas ng Point Release (PR) para sa LTR at LR branch. Ang PR sa LTR branch ay naglalaman ng mga bug-fixes. Ang PR naman sa LR branch ay naglalaman ng bug-fixes at mga bagong features.


## Anong bersyon ang dapat kong gamitin?
**Depende sa user.**
Kung kailangan mo ng bersyon na supported ng mas matagal at hindi mo naman masyadong kailangan ang mga bagong features, mainam gamitin ang LTR.
Kung ang nais mo naman ay magkaroon ng mga pinakabagong features ng QGIS at hindi issue ang pag-uupgrade kada ilang buwan, mainam gamitin ang LR.
Mainam din minsan tingnan ang Development version lalo na kung curious or excited kang magamit ang mga paparating na features ng QGIS.


## TL;DR
- May tatlong branches (o bersyon) ng QGIS na maaring i-install: Long Term Release (LTR), Latest Release (LR), o Development (Nightly).
- Ang LTR ay makakatangap ng bug-fixes hanggang ilabas ang susunod na LTR subalit maaring wala itong mga features na mayroon sa LR.
- Ang LR naman ay nagtataglay ng mga pinaka-bagong features ng QGIS.
- Bawat apat na buwan ay may bagong release version na nilalabas para sa LTR at LR.
- Bawat buwan ay may Point Release na nilalabas para sa LTR at LR.


## BONUS 1: Quantum GIS ba o QGIS?
Marahil ay nakilala natin ang QGIS noong kabataan niya kung kailan kilala pa siya bilang Quantum GIS subalit alam niyo ba na simula QGIS 2 (2013) ay [opisyal nang pinalitan ang pangalan sa QGIS mula sa Quantum GIS](https://www.qgis.org/en/site/forusers/visualchangelog200/index.html#feature-quantum-gis-is-now-known-only-as-qgis). Samakatuwid, mas mainam na gamitin ang QGIS o Q imbes na Quantum GIS sa pagtukoy ng QGIS.


## BONUS 2: Mga pangalan ng bersyon
Sa kasalukuyan, ang mga pangalan ng bersyon ng QGIS ay hango sa mga lugar kung saan ginanap ang mga nakaraang [QGIS User Conference at Developer Meetings](https://www.qgis.org/en/site/getinvolved/meetings/developer/index.html) tulad ng Hannover, București, A Coruña, Zanzibar, Madiera, etc. Isang exception ay ang QGIS 3.14 na pinangalanang Pi.

Bago nito, ang pangalan ng mga bersyon ng QGIS noon ay hango sa mga buwan ng Saturn at Jupiter.



At iyan ang mga bagay ukol sa mga bersyon at release cycle ng QGIS. Ikaw, anong bersyon ang gamit o paborito mo? Maari ring mag-iwan ng katanungan o kumento sa ibaba.

Like and follow BNHR on [Facebook](https://facebook.com/bnhr.xyz) and [Twitter](https://twitter.com/BNHRdotXYZ) for more #FOSS4G and #QGIS stuff. :)


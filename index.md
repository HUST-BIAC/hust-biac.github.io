---
layout: page
title: 国家防伪工程技术研究中心
cover-img: /assets/img/title.jpg
---
<!--
 * @Author: Conghao Wong
 * @Date: 2023-03-08 19:13:03
 * @LastEditors: Conghao Wong
 * @LastEditTime: 2023-05-06 13:32:40
 * @Description: file content
 * @Github: https://cocoon2wong.github.io
 * Copyright 2023 Conghao Wong, All Rights Reserved.
-->

<style>
    .news_grid {
        display: grid;
        grid-template-columns: 6.5em auto;
    }

    .t_grid_01 {
        display: grid;
        grid-template-columns: 75% auto;
        grid-gap: 60px 2%;
    }
</style>

<link rel="stylesheet" type="text/css" href="/assets/css/user.css">

<div class="t_grid_back">
    <div>
        <h2>新闻快讯</h2>
    </div>
    <div style="text-align: right;">
        <a class="btn btn-info btn-lg get-started-btn btn_dark" href="/news/index">更多 ></a>
    </div>
</div>

---

<ul class="posts-list list-unstyled" role="list">
    {% for post in site.tags.news limit: 5%}
    <li>
        <div class="news_grid">
            <div>
                {% assign date_format = "%Y-%m-%d" %}
                [{{ post.date | date: date_format }}]
            </div>
            <div>
                <a href="{{ post.url | relative_url }}">
                    {{ post.title | strip_html }}
                </a>
            </div>
        </div>
    </li>
    {% endfor %}
</ul>

<p></p>

<div class="t_grid_back">
    <div>
        <h2>中心简介</h2>
    </div>
    <div style="text-align: right;">
        <a class="btn btn-info btn-lg get-started-btn btn_dark" href="/intro/introduction">更多 ></a>
    </div>
</div>

---

国家防伪工程技术研究中心于2005年3月由国家科技部批准依托华中科技大学组建，是专门从事核心防伪技术及其工程化的国家级研究开发机构和产业化基地。是我国安全防伪技术创新的源头和产业化示范基地，承担着提升我国安全防伪技术及其产品水平的重任。是中国防伪产学研联盟秘书长单位；中国防伪行业协会副理事长单位；中国防伪标准化委员会委员单位。在<strong
    class="h_01">信息安全和防伪行业</strong>，国家防伪工程技术研究中心<strong class="h_02">代表国家竞争力，具备国际竞争力</strong>。
    <a href="/intro/introduction" class="post-read-more">[Read&nbsp;More]</a>

<div class="row" style="text-align: center;">
    <img class="col-xl-3 offset-xl-0 col-lg-3 offset-lg-0" src="/assets/img/index/1.png">
    <img class="col-xl-3 offset-xl-0 col-lg-3 offset-lg-0" src="/assets/img/index/2.jpg">
    <img class="col-xl-3 offset-xl-0 col-lg-3 offset-lg-0" src="/assets/img/index/3.png">
    <img class="col-xl-3 offset-xl-0 col-lg-3 offset-lg-0" src="/assets/img/index/4.png">
</div>

<p></p>

<div class="t_grid_back">
    <div>
        <h2>学术交流</h2>
    </div>
    <div style="text-align: right;">
        <a class="btn btn-info btn-lg get-started-btn btn_dark" href="/cooperations/platform">更多 ></a>
    </div>
</div>


---

<div class="row">
    <div class="col-xl-8 offset-xl-0 col-lg-8 offset-lg-0">
        <ul class="posts-list list-unstyled" role="list">
            {% for post in site.tags.event limit: 3%}
            <li>
                <div class="news_grid">
                    <div>
                        {% assign date_format = "%Y-%m-%d" %}
                        [{{ post.date | date: date_format }}]
                    </div>
                    <div>
                        <a href="{{ post.url | relative_url }}">
                            {{ post.title | strip_html }}
                        </a>
                    </div>
                </div>
            </li>
            {% endfor %}
        </ul>
    </div>

    <div class="col-xl-4 offset-xl-0 col-lg-4 offset-lg-0" style="text-align: right">
        <img style="width: 100%;" src="/assets/img/index/1.png">
    </div>

</div>

<p></p>

<div class="t_grid_back">
    <div>
        <h2>成果推荐</h2>
    </div>
    <div style="text-align: right;">
        <a class="btn btn-info btn-lg get-started-btn btn_dark" href="/industry/index">更多 ></a>
    </div>
</div>

---

<div class="row" style="text-align: center; width: 100%;">
    <a class="btn btn-info btn-lg col-xl-4 offset-xl-0 col-lg-4 offset-lg-0 btn_dark t_button_industry" href="/industry/0">
        <img style="height: 150px;" src="/assets/img/team/l1.png">
        <br>全息防伪技术与制备工艺
    </a>
    <a class="btn btn-info btn-lg col-xl-4 offset-xl-0 col-lg-4 offset-lg-0 btn_dark t_button_industry" href="/industry/2">
        <img style="height: 150px;" src="/assets/img/team/l6.png">
        <br>防伪票据智能鉴伪与识读技术及装备
    </a>
    <a class="btn btn-info btn-lg col-xl-4 offset-xl-0 col-lg-4 offset-lg-0 btn_dark t_button_industry" href="/industry/7">
        <img style="height: 150px;" src="/assets/img/industry/7/7-1.jpg">
        <br>防伪用全息塑料及其加工技术
    </a>
</div>

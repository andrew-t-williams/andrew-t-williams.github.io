---
layout: default
title: Contact
permalink: /contact/
---
<script src="https://code.iconify.design/2/2.1.0/iconify.min.js"></script>

<div class="wrapper">
    <div class="row">
        <div class="col">
            <div style="height: 100%; width: 60%; float: left; background-color: #161b22; padding: 20px 0px 20px 100vw; margin-left: -100vw; margin-top: -20px;">
                <div style="height: 40%;"></div>
                <h1 style="font-size: 35px; color: #34a55c; font-family: monospace;">{{ site.name }}<span class="terminal">_</span></h1>
            </div>
            <div style="width: 30%; float: right; background-color: #161b22; padding: 20px 100vw 20px 10%; margin: -20px -100vw -20px -10%;">
                <img style="border-radius: 50%; width: -moz-available; width: -webkit-fill-available;" src="{{ site.baseurl }}/assets/images/profile.jpg">
            </div>
        </div>
    </div>
    <div class="row">
        <div class="col">
            <br><br>
            <p>{{ site.about_me }}</p>
            <div style="float: left; height: 26px; width: 100%;"><hr></div>
            <div style="float: left; width: 100%;">
                <a href="mailto:{{ site.email }}" style="float: left; margin-right: 10px; margin-top: 4px;">
                    <h1 style="float: left;">
                        <span class="iconify" data-icon="entypo:mail" style="color: white;"></span>
                    </h1>
                </a>
                <a href="mailto:{{ site.email }}" style="width: calc(100% - 70px); float: left;">
                    <pre><code>{{ site.email }}</code></pre>
                </a>
                <div class="tooltip" style="float: right;">
                    <button id="mailto" onclick="clipboardClick('{{ site.email }}','emailtooltip')" onmouseout="clipboardHover('emailtooltip')" style="padding: 0px; border: 0px; background: none;">
                        <span class="tooltiptext" id="emailtooltip"></span>
                        <span class="iconify" data-icon="clarity:copy-to-clipboard-line" style="color: white; height: 25px; width: 25px; margin-top: 6px;"></span>
                    </button>
                </div>
            </div>
            <div style="float: left; width: 100%;">
                <a href="tel:{{ site.phone }}" style="float: left; margin-right: 10px; margin-top: 4px;">
                    <h1>
                        <span class="iconify" data-icon="el:phone-alt" style="color: white;"></span>
                    </h1>
                </a>
                <a href="tel:{{ site.phone }}" style="width: calc(100% - 70px); float: left;">
                    <pre><code>{{ site.phone }}<small style="float:right;">{{ site.timezone_note }}</small></code></pre>
                </a>
                <div class="tooltip" style="float: right;">
                    <button id="mailto" onclick="clipboardClick('{{ site.phone }}','phonetooltip')" onmouseout="clipboardHover('phonetooltip')" style="padding: 0px; border: 0px; background: none;">
                        <span class="tooltiptext" id="phonetooltip"></span>
                        <span class="iconify" data-icon="clarity:copy-to-clipboard-line" style="color: white; height: 25px; width: 25px; margin-top: 6px;"></span>
                    </button>
                </div>
            </div>
            <div style="float: left; width: 100%;">
                <a href="{{ site.github_url }}" style="float: left; margin-right: 10px; margin-top: 4px;" target="_blank" rel="noopener noreferrer">
                    <h1>
                        <span class="iconify" data-icon="octicon:mark-github-16" style="color: white;"></span>
                    </h1>
                </a>
                <a href="{{ site.github_url }}" style="width: calc(100% - 70px); float: left;">
                    <pre><code>{{ site.github_url_short }}</code></pre>
                </a>
                <div class="tooltip" style="float: right;">
                    <button id="mailto" onclick="clipboardClick('{{ site.github_url }}','gittooltip')" onmouseout="clipboardHover('gittooltip')" style="padding: 0px; border: 0px; background: none;">
                        <span class="tooltiptext" id="gittooltip"></span>
                        <span class="iconify" data-icon="clarity:copy-to-clipboard-line" style="color: white; height: 25px; width: 25px; margin-top: 6px;"></span>
                    </button>
                </div>
            </div>
            <div style="float: left; width: 100%;">
                <a href="{{ site.linkedin_url }}" style="float: left; margin-right: 10px; margin-top: 4px;" target="_blank" rel="noopener noreferrer">
                    <h1>
                        <span class="iconify" data-icon="akar-icons:linkedin-fill" style="color: white;"></span>
                    </h1>
                </a>
                <a href="{{ site.linkedin_url }}" style="width: calc(100% - 70px); float: left;">
                    <pre><code>{{ site.linkedin_url_short }}</code></pre>
                </a>
                <div class="tooltip" style="float: right;">
                    <button id="mailto" onclick="clipboardClick('{{ site.linkedin_url }}','linkedintooltip')" onmouseout="clipboardHover('linkedintooltip')" style="padding: 0px; border: 0px; background: none;">
                        <span class="tooltiptext" id="linkedintooltip"></span>
                        <span class="iconify" data-icon="clarity:copy-to-clipboard-line" style="color: white; height: 25px; width: 25px; margin-top: 6px;"></span>
                    </button>
                </div>
            </div>
            <script>
                function clipboardClick(text, tooltip) {
                    navigator.clipboard.writeText(text);
                    var tooltip = document.getElementById(tooltip);
                    tooltip.innerHTML = "Copied. 👌";
                }
                function clipboardHover(tooltipID) {
                    var tooltip = document.getElementById(tooltipID);
                    tooltip.innerHTML = "Copy to clipboard. ";
                }
            </script>
        </div>
    </div>
</div>


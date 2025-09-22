---
layout: default
title: Final Project Part I
---

# The Trader Joe's Effect: How a Grocery Store Transforms Pittsburgh Neighborhoods

## Project Overview

When people think about what drives neighborhood property values, they typically consider factors like schools, crime rates, or proximity to downtown. But what if I told you that a grocery store—specifically Trader Joe's—could be one of the most reliable predictors of rising home prices?

The "Trader Joe's Effect" describes the measurable impact that opening a Trader Joe's store has on surrounding property values. This phenomenon goes beyond simple convenience; Trader Joe's locations often become community anchors that signal and accelerate neighborhood transformation. For homeowners and potential buyers, understanding this effect could influence major financial decisions.

This project will examine whether the Trader Joe's Effect holds true in Pittsburgh, analyzing housing price changes around the city's three locations over nearly two decades. Through data visualization, I'll explore not just whether prices rise, but when, how much, and how far the effect extends geographically.

## Story Structure

**Setup: The Neighborhood Game-Changer**

- Introduction to the concept: What is the Trader Joe's Effect?
- Why it matters: The intersection of retail, community, and real estate

**Investigation: Pittsburgh as a Case Study**

- Mapping Pittsburgh's three Trader Joe's locations and their opening timeline
- Establishing baseline: What were these neighborhoods like before TJ arrived?

**The Data Story: Following the Price Trail**

- Time series analysis showing housing price changes before and after store openings
- Geographic analysis: How far does the effect extend from each store?
- Comparison with control neighborhoods to isolate the Trader Joe's impact

**Implications: What This Means for Pittsburgh**

- For homebuyers: Should proximity to Trader Joe's influence your housing search?
- For communities: What does this reveal about neighborhood development patterns?
- Looking ahead: Can we predict where Pittsburgh's next location might open?

## Target Audience & Key Message

**Primary Audience:** Pittsburgh-area residents considering buying a home or curious about neighborhood development patterns.

**Key Message:** The presence of certain retail anchors like Trader Joe's can significantly impact property values, and understanding these patterns can inform smarter housing and investment decisions.

## Initial Data Analysis & Sketches

<div class='tableauPlaceholder' id='viz1758558046277' style='position: relative'>
<noscript>
<a href='#'>
<img alt='Pittsburgh Trader Joe&#39;s Neighborhood House Price ' src='https://public.tableau.com/static/images/tr/traderjoes/Sheet1/1_rss.png' style='border: none' />
</a>
</noscript>
<object class='tableauViz' style='display:none;'>
<param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
<param name='embed_code_version' value='3' />
<param name='site_root' value='' />
<param name='name' value='traderjoes/Sheet1' />
<param name='tabs' value='no' />
<param name='toolbar' value='yes' />
<param name='static_image' value='https://public.tableau.com/static/images/tr/traderjoes/Sheet1/1.png' />
<param name='animate_transition' value='yes' />
<param name='display_static_image' value='yes' />
<param name='display_spinner' value='yes' />
<param name='display_overlay' value='yes' />
<param name='display_count' value='yes' />
<param name='language' value='en-US' />
<param name='filter' value='publish=yes' />
</object>
</div>
<script type='text/javascript'>
var divElement = document.getElementById('viz1758558046277');
var vizElement = divElement.getElementsByTagName('object')[0];
vizElement.style.width='100%';
vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
var scriptElement = document.createElement('script');
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

Based on preliminary analysis of Zillow Housing Value Index data, I'm examining three distinct Pittsburgh markets:

- **East Liberty (2006):** The pioneer location that opened during a period of significant neighborhood revitalization
- **North Hills/McCandless (2015):** A suburban location in an already-established area
- **South Hills (2025):** The newest location, providing real-time data on immediate impacts

## Data Sources & Methodology

**Primary Data:**

- [**Zillow Home Value Index (ZHVI)](https://www.zillow.com/research/data/):** Monthly median home values by ZIP code, 2000-2024
- **Trader Joe's Store Data:** Opening dates and addresses confirmed through press releases and local news archives. Utilize Perplexity to collect the information
- **Census/ACS Data:** Demographic context for each neighborhood

**Analysis Approach:**

- Time series analysis comparing 5-year periods before and after store openings
- Geographic analysis using concentric circles (0.5, 1.0, 2.0-mile radius from stores)
- Control group comparison with similar Pittsburgh ZIP codes without Trader Joe's

**Limitations to Address:**

- Correlation vs. causation: TJ may choose neighborhoods already trending upward
- External factors: Other development projects, market conditions, demographic shifts

## Method & Medium

**Platform:** Shorthand for the narrative story structure with embedded Tableau table
**Visualizations:** Tableau for time series charts, maps, and comparative analysis
**Additional Elements:**

- Interactive map allowing users to explore different radius effects
- Timeline slider showing price changes over years
- Comparative tool for users to see their own neighborhood's trajectory

The final deliverable will be a compelling, data-driven story that Pittsburgh residents can use to better understand their local housing market while exploring a fascinating intersection of retail psychology and urban development.

## References
- Scott, Diamond-Michael. “The “Trader Joe’s Effect" On Community and Economic Development.” Substack newsletter. Great Books + Great Cities, 18 Dec. 2023, https://greatbooksgreatcities.substack.com/p/the-trader-joes-effect-on-community.
- Zillow Research: https://www.zillow.com/research/data/ 

## AI acknowledgements
_If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here._

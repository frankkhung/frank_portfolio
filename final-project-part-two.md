---
layout: default
title: Final Project Part II
---

# Wireframes / storyboards
[Shorthand Storyboard](https://preview.shorthand.com/7agkB6xhv5SzRpyh/responsive/desktop)

# User Research and Interviews

## Target Audience

**Primary**: Pittsburgh residents aged 25-45 interested in buying/renting homes or understanding neighborhood development

Why this audience: This demographic is actively making housing decisions and needs data driven insights to evaluate neighborhoods. They might encounter real estate agents claiming “There’s Trader Joe’s down the neighborhood” and need to understand whether this phenomenon is real or myth, especially in Pittsburgh area.

**Secondary**: Real Estate Professionals and Urban Planning students

**What they are expecting from this story:**

- Clear answer to “Does proximity to Trader Joe’s affect home values?”
- Practical guidance for home-buying or home-renting decisions.
- Understanding of broader neighborhood development factors

## Interviewees

**Selection Criteria**: I recruited 3 individuals within my target audience to ensure diverse feedback.

**Recruitment Method**: Personal Network and CMU community

**Interviewee #1 Profile**: Student in Pittsburgh who is renting an apartment

**Interviewee #2 Profile**: Student in Pittsburgh who is renting an apartment

**Interviewee #3 Profile**: Non-US Resident who has extensive understanding in real estate

## Interview Script

*I'm working on a data story about the 'Trader Joe's Effect'—the idea that homes near Trader Joe's stores increase in value faster than other homes. I'm specifically testing whether this phenomenon holds true in Pittsburgh.*

*I'm going to show you my draft story in Shorthand. It's still a work in progress—some parts are finished, some are rough sketches. As you look through it, I'd love for you to think aloud. Tell me what you're noticing, what makes sense, what's confusing, what's interesting.*

## Question

### Initial Impressions

- **"What's your first reaction? What do you think this story is about?"**
- **"Does the opening grab your attention? Why or why not?"**
- **"Is anything confusing so far?"**

### Data Visualizations

- **"Walk me through what you see in this map/chart. What story does it tell?"**
- **"Is anything confusing or hard to understand in these visualizations?"**
- **"What additional information would help you interpret these charts?"**
- **For the control group: "Why am I comparing neighborhoods with and without TJ?"**

### Overall Assessment

- **"If you had to explain this project to a friend in one sentence, what would you say?"**
- **"What was the strongest part of the story?"**
- **"What was the weakest or most confusing part?"**
- **"Any other feedback or suggestions?"**

## Interview Result

<table style="border-collapse: collapse; width: 100%; border: 2px solid black;">
  <thead>
    <tr style="background-color: #f2f2f2;">
      <th style="border: 1px solid black; padding: 12px; text-align: left; font-weight: bold;">Category</th>
      <th style="border: 1px solid black; padding: 12px; text-align: left; font-weight: bold;">Interviewee #1</th>
      <th style="border: 1px solid black; padding: 12px; text-align: left; font-weight: bold;">Interviewee #2</th>
      <th style="border: 1px solid black; padding: 12px; text-align: left; font-weight: bold;">Interviewee #3</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="border: 1px solid black; padding: 12px; vertical-align: top; font-weight: bold;">INITIAL REACTIONS</td>
      <td style="border: 1px solid black; padding: 12px; vertical-align: top;">
        <strong>Positive:</strong><br>
        • Background story explains concept well and is motivating<br>
        • Questions answered progressively<br>
        • Opening grabs attention<br><br>
        <strong>Issues:</strong><br>
        • Not clear the story pivots to <em>testing</em> whether TJ drives prices<br>
        • Expected to see price data earlier<br>
        • Quote: "It wasn't clear we pivoted to choosing to prove whether it drives the housing price"<br>
        • Needs earlier hint at conclusion/testing approach
      </td>
      <td style="border: 1px solid black; padding: 12px; vertical-align: top;">
        <strong>Positive:</strong><br>
        • The theme is very clear with the color<br>
        <strong>Issues:</strong><br>
        • Probably because it's a draft with some content lacking so the logic flow isn't that strong.
      </td>
      <td style="border: 1px solid black; padding: 12px; vertical-align: top;">
        <strong>Positive:</strong><br>
        • Finds topic very interesting<br>
        • Logic holds and makes sense overall<br><br>
        <strong>Issues:</strong><br>
        • Quote: "The logic hold and it makes sense, but it's not convincing yet"<br>
        • Doesn't show enough information to reach the conclusion<br>
        • Assumption issue: "People wouldn't be directly thinking trader joe's is driving the housing market up"<br>
        • Story assumes reader believes TJ drives prices, but many may not
      </td>
    </tr>
    <tr>
      <td style="border: 1px solid black; padding: 12px; vertical-align: top; font-weight: bold;">DATA VISUALIZATIONS</td>
      <td style="border: 1px solid black; padding: 12px; vertical-align: top;">
        <strong>What Worked:</strong><br>
        • Time series showing prices rising is clear<br>
        • Following sections answer "is this just market trend?"<br><br>
        <strong>Confusion:</strong><br>
        • Control group selection unclear<br>
        • Quote: "Don't know why I chose these neighborhoods"<br>
        • Tableau formatting issues<br><br>
        <strong>Missing Info:</strong><br>
        • Wants citywide Pittsburgh average for comparison<br>
        • Quote: "Average price of the entire Pittsburgh to be able to compare and contrast"<br>
        • Needs explanation of why control neighborhoods chosen
      </td>
      <td style="border: 1px solid black; padding: 12px; vertical-align: top;">
        <strong>What Worked:</strong><br>
        • The graph is clear but I would wonder how other areas' home value look like<br><br>
        <strong>Confusion:</strong><br>
        • <strong>Labeling issues:</strong><br>
          - Quote: "Wording in the label is confusing"<br>
        • <strong>Tableau formatting problems</strong> (consistent issue)<br>
        • <strong>Control group needs explanation:</strong><br>
          - Quote: "I would want to know the reason why it's selected"<br>
      </td>
      <td style="border: 1px solid black; padding: 12px; vertical-align: top;">
        <strong>What Worked:</strong><br>
        • Can see all neighborhoods trending upwards<br><br>
        <strong>Confusion:</strong><br>
        • <strong>Labeling issues:</strong><br>
          - Quote: "Wording in the label is confusing → Change to opening date"<br>
          - ZIP code numbers not clear to non-Americans<br>
          - Quote: "For non-american, they wouldn't know the number is indicating ZIP code. Better labeling"<br>
        • <strong>Tableau formatting problems</strong> (consistent issue)<br>
        • <strong>Control group needs explanation:</strong><br>
          - Quote: "Get what it's about after thinking about it. Should have some explanation before to make it more intuitive"<br>
          - Understanding comes eventually but requires too much cognitive effort
      </td>
    </tr>
    <tr>
      <td style="border: 1px solid black; padding: 12px; vertical-align: top; font-weight: bold;">OVERALL THOUGHTS</td>
      <td style="border: 1px solid black; padding: 12px; vertical-align: top;">
        <strong>Strongest:</strong><br>
        • Conclusion ties everything together<br>
        • Quote: "The last part conclusion is similar to what I have arrived at in my head"<br><br>
        <strong>Weakest:</strong><br>
        • Market trend section feels disconnected<br>
        • Quote: "Don't know why it's in this section"<br>
        • Quote: "Not hinted earlier"<br>
        • Needs better foreshadowing of testing approach
      </td>
      <td style="border: 1px solid black; padding: 12px; vertical-align: top;">
        <strong>Strongest:</strong><br>
        • I think I read something similiar somewhere and this article conveys the idea well. And finds other ways to justify when you can't find the clear effect.
        <strong>Weakest:</strong><br>
        • How about other stores? Why are you only listing out East Liberty?
      </td>
      <td style="border: 1px solid black; padding: 12px; vertical-align: top;">
        <strong>Strongest:</strong><br>
        • Very interesting topic<br>
        • Logic flows reasonably well<br><br>
        <strong>Weakest:</strong><br>
        • <strong>Too many "BUT" transitions:</strong><br>
          - Quote: "Too many slides that start with the word 'BUT'"<br>
          - Creates negative/contradictory feeling<br>
          - Weakens narrative momentum<br>
        • <strong>Section linkages unclear:</strong><br>
          - Quote: "The last few sections are confusing. Linkage between the sections is not direct"<br>
          - "East liberty → But the market trend problem, and what it's about, could be clearer"<br>
        • <strong>Insufficient evidence:</strong><br>
          - Quote: "Did not show enough information to reach the conclusion"<br>
          - "What's making Pittsburgh's housing market unique" needs more support
      </td>
    </tr>
  </tbody>
</table>

## Improvements

### 1. **Clarify the Pivot to Testing Earlier**
Multiple interviewees were confused about when the story shifts from exploring the concept to actually *testing* whether Trader Joe's drives housing prices. Foreshadow your testing approach and hypothesis earlier in the presentation so readers know where you're headed.

### 2. **Explain Control Group Selection**
Both interviewees were confused about why specific control neighborhoods were chosen. Add clear explanations about your methodology for selecting comparison neighborhoods before showing the data visualizations.

### 3. **Reduce "BUT" Transitions**
Interviewee #3 noted too many sections starting with "BUT," which creates a negative, contradictory feeling and weakens narrative momentum. Restructure transitions to build your argument more positively and cohesively.

### 4. **Improve Section Linkages**
The connection between sections (especially the market trend analysis) feels disconnected and unclear. Make the logical flow between sections more explicit so readers understand how each piece contributes to your overall conclusion.

### 5. **Provide More Supporting Evidence**
Interviewees felt the conclusion wasn't fully supported by the data presented. Add more evidence (like citywide Pittsburgh averages for comparison) and show sufficient information to make your conclusion convincing rather than just logically sound.

## References
- Scott, Diamond-Michael. “The “Trader Joe’s Effect" On Community and Economic Development.” Substack newsletter. Great Books + Great Cities, 18 Dec. 2023, https://greatbooksgreatcities.substack.com/p/the-trader-joes-effect-on-community.
- Zillow Research: https://www.zillow.com/research/data/ 

## AI acknowledgements
I will be using Perplexity to scrap Trader Joe's News on store opening date.
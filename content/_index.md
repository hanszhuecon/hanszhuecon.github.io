---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: |
        [hanszhu2024@u.northwestern.edu](mailto:hanszhu2024@u.northwestern.edu)
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded

  # ---------- WORKING PAPERS ----------
  - block: markdown
    id: working-papers
    content:
      title: "Working Papers"
      text: |
        * **Limiting For-profit Provision in Nursing Home Markets**  
          with [Hyein Cho](https://hyeinhcho.github.io/) — *latest draft: November 2025*  
          [PDF](/files/zhu_kim_rbc_pass_through.pdf)

          _Abstract:_ We examine whether policies that ban for-profit providers and allow for subsequent takeovers by not-for-profits can be effective at addressing quality shortfalls. We consider the US nursing home industry, where quality provision has been a concern for many decades. Our motivating evidence suggests that not-for-profit providers choose higher-quality inputs than their for-profit counterparts but are more prevalent in higher socioeconomic markets and serve wealthier residents. Thus, for-profit providers play an important role in providing access. To explain these facts and explore counterfactual policies, we estimate a structural model of nursing home demand and supply that allows firms to have nonpecuniary motives and costs that differ across provider types. The structural model reveals that for-profit providers have a strong cost advantage for serving needier residents. This results in them choosing a lower quality and lower priced product to maximise their margins. Not-for-profit providers choose higher quality, and therefore higher prices, not because of their nonpecuniary motive, but because they prefer to avoid directly competing with for-profit providers by serving residents with stronger preferences for quality. Therefore, banning for-profit providers while allowing for takeovers tends to reduce consumer surplus because not-for-profits that take over for-profits significantly raise prices to cover their higher costs. These results underscore the role that for-profit providers play in expanding access to nursing home care.

        * **Could it be Better to Refund than Recommend? The Role of Ex-post Match Values in Digital Entertainment Markets**

          _Abstract:_ Digital entertainment markets are characterised by many niches and the 'long tail' of consumption. I argue that the size of these tails may be dramatically underestimated if ex-post match values - match values realised only after consumption - are not taken into account. I collect a novel individual-level dataset on the Steam platform and interpret playtime data as directly informative about ex-post match values. The playtime data reveal patterns of consumption starkly different to those inferred from purchases. I then examine the policy relevance of ex-post match values, by studying a unique series of policy changes on the Steam platform. The introduction of personalised stores followed by the introduction of refunds. Personalised stores should improve consumer matches on average, but are unable to recommend on the basis of realised ex-post match values. Refunds allow consumers to realise ex-post match values before committing to the purchase. I find that sales increase following the introduction of refunds by around 5 times the increase following the introduction of personalised stores. In addition, the sales patterns following the introduction of refunds are dramatically different compared to those with the introduction of personalised stores. These results suggest that the effects of personalised stores alone are limited. Whether personalised stores matter or are complementary to refunds will be investigated using a structural model which I describe.

  # ---------- WORKS IN PROGRESS ----------
  - block: markdown
    id: works-in-progress
    content:
      title: "Works in Progress"
      text: |
        * **Labor market spillovers of regulated pricing in the US nursing homes industry**

          _Abstract:_ Complaints of labor shortages are common in health and education markets where prices are often fixed or regulated. In this project, I argue that the two are linked. The ability of providers to adjust their labor inputs depends on their ability to adjust wages which is limited when they face regulated prices. I study this idea in the US nursing homes industry, where a significant proportion of revenues that providers receive are from fixed prices. In addition to a structural model of nursing home demand and supply, I model nurse labor supply. This will allow me to consider counterfactuals where nursing homes can freely set prices and study the resulting implications on nursing home quality and the nurse labor market.

        * **Financial-Regulation Pass-through to Consumers in the U.S. Life-Insurance Industry**  
          with [Paul Kim](https://sites.google.com/view/paul-hs-kim/home)

          _Abstract:_ Life- and long-term-care (LTC) insurers back their long-duration liabilities with sizable bond portfolios. Accordingly, solvency regulation effectively restricts the riskiness and expected returns of an insurer's investment portfolio. However, since expected returns govern the profitability of offering insurance, solvency regulation also affects premium pricing. In this paper, we study the pass-through to consumers of a change in solvency regulation in the US life insurance industry. The National Association of Insurance Commissioners (NAIC) increased risk charges for NAIC 2 (BBB) long-term bonds in 2022. This effectively increased the capital requirements for holding these bonds, reducing their expected returns. We construct a shift-share instrument using the increase in risk charges for NAIC 2 bonds, with exposure to the shock being captured by exposure to NAIC 2 bonds and how binding their financial constraints are. The instrument will be used to estimate the pass-through from reducing acquisitions of NAIC 2 bonds to higher insurance premia.
    
---

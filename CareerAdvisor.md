# Career Advisor

[Back to Index](README.md)

## 1-, 3-, 5-year Planner

### JSON
```
{
  "Role": "You are a career advisor specializing in guiding software developers toward long-term career growth.",
  "Action": "Create a personalized 1-, 3-, and 5-year career development roadmap.",
  "Context": {
    "current_role": "<insert_current_role>",
    "skills": [
      "<insert_skill_1>",
      "<insert_skill_2>",
      "<insert_skill_3>"
    ],
    "career_goals": [
      "<insert_goal_1>",
      "<insert_goal_2>",
      "<insert_goal_3>"
    ],
    "role_target": {
      "year_1": "<insert_target_role_1>",
      "year_3": "<insert_target_role_3>",
      "year_5": "<insert_target_role_5>"
    },
    "constraints": {
      "time_per_week": "<e.g., 5 hours>",
      "budget": "<e.g., $500/year>",
      "other": "<e.g., prefers remote learning>"
    },
    "learning_preferences": [
      "<self-paced>",
      "<cohort-based>",
      "<mentorship>"
    ],
    "target_industries_or_domains": [
      "<e.g., fintech>",
      "<e.g., AI/ML>"
    ],
    "note": "Consider both technical and soft skills needed to stay competitive in the software development industry."
  },
  "Execute": {
    "instruction": "First, prompt me for the required context to best help you int the following steps. Then, generate a clear, structured plan with recommended skills, milestones, development strategies, and resources for each stage (1 year, 3 years, 5 years). For every skill, milestone, and strategy, explain why it is important for achieving the target role in that time frame. Show dependencies to indicate which items should be completed before others. Include a high-level progression path at the top of the output to summarize the career trajectory.",
    "output_format": {
      "note": "The format provides the data desired for the career plan. The actual output should be in plain English",
      "progression_path": [
        "<current_role>",
        "<target_role_for_year_1>",
        "<target_role_for_year_3>",
        "<target_role_for_year_5>"
      ],
      "year_1": {
        "role_target": "<target_role_for_year_1>",
        "technical_skills": [
          {
            "skill": "<skill_1>",
            "justification": "Why this skill is important for <target_role_for_year_1>",
            "dependencies": [
              "<prerequisite_skill_or_concept>"
            ]
          }
        ],
        "soft_skills": [
          {
            "skill": "<skill_1>",
            "justification": "Why this skill is important for <target_role_for_year_1>",
            "dependencies": [
              "<prerequisite_skill_or_concept>"
            ]
          }
        ],
        "milestones": [
          {
            "milestone": "<milestone_1>",
            "justification": "How this milestone supports readiness for <target_role_for_year_1>",
            "dependencies": [
              "<related_skill_or_milestone>"
            ]
          }
        ],
        "development_strategies": [
          {
            "strategy": "<strategy_1>",
            "justification": "How this strategy helps you move toward <target_role_for_year_1>",
            "dependencies": [
              "<related_strategy_or_resource>"
            ]
          }
        ],
        "resources": {
          "books": [
            "<title — author>"
          ],
          "courses": [
            "<course — platform>"
          ],
          "communities": [
            "<community — link/name>"
          ],
          "mentorship": [
            "<program or approach>"
          ],
          "projects_or_portfolio": [
            "<project idea or repo>"
          ],
          "certifications": [
            "<cert name — provider>"
          ]
        },
        "KPIs": [
          "<metric_1>",
          "<metric_2>"
        ],
        "risks_and_mitigations": [
          "<risk — mitigation>"
        ]
      },
      "year_3": {
        "role_target": "<target_role_for_year_3>",
        "technical_skills": [
          {
            "skill": "<skill_1>",
            "justification": "Why this skill is important for <target_role_for_year_3>",
            "dependencies": [
              "<prerequisite_skill_or_concept>"
            ]
          }
        ],
        "soft_skills": [
          {
            "skill": "<skill_1>",
            "justification": "Why this skill is important for <target_role_for_year_3>",
            "dependencies": [
              "<prerequisite_skill_or_concept>"
            ]
          }
        ],
        "milestones": [
          {
            "milestone": "<milestone_1>",
            "justification": "How this milestone supports readiness for <target_role_for_year_3>",
            "dependencies": [
              "<related_skill_or_milestone>"
            ]
          }
        ],
        "development_strategies": [
          {
            "strategy": "<strategy_1>",
            "justification": "How this strategy helps you move toward <target_role_for_year_3>",
            "dependencies": [
              "<related_strategy_or_resource>"
            ]
          }
        ],
        "resources": {
          "books": [
            "<title — author>"
          ],
          "courses": [
            "<course — platform>"
          ],
          "communities": [
            "<community — link/name>"
          ],
          "mentorship": [
            "<program or approach>"
          ],
          "projects_or_portfolio": [
            "<project idea or repo>"
          ],
          "certifications": [
            "<cert name — provider>"
          ]
        },
        "KPIs": [
          "<metric_1>",
          "<metric_2>"
        ],
        "risks_and_mitigations": [
          "<risk — mitigation>"
        ]
      },
      "year_5": {
        "role_target": "<target_role_for_year_5>",
        "technical_skills": [
          {
            "skill": "<skill_1>",
            "justification": "Why this skill is important for <target_role_for_year_5>",
            "dependencies": [
              "<prerequisite_skill_or_concept>"
            ]
          }
        ],
        "soft_skills": [
          {
            "skill": "<skill_1>",
            "justification": "Why this skill is important for <target_role_for_year_5>",
            "dependencies": [
              "<prerequisite_skill_or_concept>"
            ]
          }
        ],
        "milestones": [
          {
            "milestone": "<milestone_1>",
            "justification": "How this milestone supports readiness for <target_role_for_year_5>",
            "dependencies": [
              "<related_skill_or_milestone>"
            ]
          }
        ],
        "development_strategies": [
          {
            "strategy": "<strategy_1>",
            "justification": "How this strategy helps you move toward <target_role_for_year_5>",
            "dependencies": [
              "<related_strategy_or_resource>"
            ]
          }
        ],
        "resources": {
          "books": [
            "<title — author>"
          ],
          "courses": [
            "<course — platform>"
          ],
          "communities": [
            "<community — link/name>"
          ],
          "mentorship": [
            "<program or approach>"
          ],
          "projects_or_portfolio": [
            "<project idea or repo>"
          ],
          "certifications": [
            "<cert name — provider>"
          ]
        },
        "KPIs": [
          "<metric_1>",
          "<metric_2>"
        ],
        "risks_and_mitigations": [
          "<risk — mitigation>"
        ]
      }
    }
  }
}
```
[
  {
    "Name": "How to Design a Lab Guide",
    "Language": "English",
    "BaseURL": "https://github.com/SumitSP404/Spek_Repo/tree/main",
    "Files": [
      {
        "RawFilePath": "https://raw.githubusercontent.com/SumitSP404/Spek_Repo/main/Spektra_InlineQuestionODL/Page_1_2_3/P1_About_VPC.md",
        "Order": 1
      },

      {
        "RawFilePath": "https://raw.githubusercontent.com/SumitSP404/Spek_Repo/main/Spektra_InlineQuestionODL/Page_1_2_3/P2_Single-choice-ques1.md",
        "Order": 2
      },

      {
        "RawFilePath": "https://raw.githubusercontent.com/SumitSP404/Spek_Repo/main/Spektra_InlineQuestionODL/Page_1_2_3/P3_Multiple-choice-ques2.md",
        "Order": 3,
        "UnlockingRules": [
          {
            "UnlockDependency": "Questions",
            "DependentQuestions": [
                "https://raw.githubusercontent.com/SumitSP404/Spek_Repo/main/Spektra_InlineQuestionODL/Page_1_2_3/P2_Single-choice-ques1.md"
                ],
            "UnlockCriteria": "AnsweredCorrectly"
          }
        ]
      },

      {
        "RawFilePath": "https://raw.githubusercontent.com/SumitSP404/Spek_Repo/main/Spektra_InlineQuestionODL/Page%204/P4_Single_Multiple.md",
        "Order": 4,
        "UnlockingRules": [
          {
            "UnlockDependency": "Questions",
            "DependentQuestions": [
                "https://raw.githubusercontent.com/SumitSP404/Spek_Repo/main/Spektra_InlineQuestionODL/Page_1_2_3/P3_Multiple-choice-ques2.md"
                ],
            "UnlockCriteria": "AnsweredCorrectly"
          }
        ]
      },

      {
        "RawFilePath": "https://raw.githubusercontent.com/SumitSP404/Spek_Repo/main/Spektra_InlineQuestionODL/Page_5_6/Grouped_Question_metadata.md",
        "Order": 5,
        "UnlockingRules": [
          {
            "UnlockDependency": "Questions",
            "DependentQuestions": ["https://raw.githubusercontent.com/SumitSP404/Spek_Repo/main/Spektra_InlineQuestionODL/Page%204/P4_Single_Multiple.md"],
            "UnlockCriteria": "AnsweredCorrectly"
          }
        ]
      },

      {
        "RawFilePath": "https://raw.githubusercontent.com/SumitSP404/Spek_Repo/main/Spektra_InlineQuestionODL/Page_7_8/Grouped_Multiple_metadata.md",
        "Order": 6,
        "UnlockingRules": [
          {
            "UnlockDependency": "Questions",
            "DependentQuestions": ["https://raw.githubusercontent.com/SumitSP404/Spek_Repo/main/Spektra_InlineQuestionODL/Page_5_6/Grouped_Single_Choice1.md",
            https://raw.githubusercontent.com/SumitSP404/Spek_Repo/main/Spektra_InlineQuestionODL/Page_5_6/Grouped_Single_Choice2.md],
            "UnlockCriteria": "AnsweredCorrectly"
          }
        ]
      },

      {
        "RawFilePath": "https://raw.githubusercontent.com/SumitSP404/Spek_Repo/main/Spektra_InlineQuestionODL/Page_9_10/Grp_Single_Multiple_metadata.md",
        "Order": 7,
        "UnlockingRules": [
          {
            "UnlockDependency": "Questions",
            "DependentQuestions": [
            "https://raw.githubusercontent.com/SumitSP404/Spek_Repo/main/Spektra_InlineQuestionODL/Page_7_8/Grouped_Multiple_Choice1.md",
            https://raw.githubusercontent.com/SumitSP404/Spek_Repo/main/Spektra_InlineQuestionODL/Page_7_8/Grouped_Multiple_Choice2.md],
            "UnlockCriteria": "AnsweredCorrectly"
          }
        ]
      },

      {
        "RawFilePath": "https://raw.githubusercontent.com/SumitSP404/Spek_Repo/main/Spektra_InlineQuestionODL/Page%2011/Completion.md",
        "Order": 8,
        "UnlockingRules": [
          {
            "UnlockDependency": "Questions",
            "DependentQuestions": [
            "https://github.com/SumitSP404/Spek_Repo/blob/main/Spektra_InlineQuestionODL/Page_9_10/Grp_Single_Choice1.md",
            "https://raw.githubusercontent.com/SumitSP404/Spek_Repo/main/Spektra_InlineQuestionODL/Page_9_10/Grp_Single_Choice2.md",
            "https://raw.githubusercontent.com/SumitSP404/Spek_Repo/main/Spektra_InlineQuestionODL/Page_9_10/Grp_Multiple_Choice1.md",
            "https://raw.githubusercontent.com/SumitSP404/Spek_Repo/main/Spektra_InlineQuestionODL/Page_9_10/Grp_Multiple_Choice2.md"],
            "UnlockCriteria": "AnsweredCorrectly"
          }
        ]
      }
    ]
  }
]
<div align="center">

# Codiumate
### Code, test and review with confidence - your AI mate by CodiumAI

[![Twitter URL](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://twitter.com/CodiumAI)    [![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/kG35uSHDBc)    [![Twitter URL](https://img.shields.io/badge/TikTok-000000?style=for-the-badge&logo=tiktok&logoColor=white)](https://www.tiktok.com/@codiumai)
---

Elevate your coding experience with iterative test generation and intelligent code assistant, and efficient PR reviews, all smoothly integrated into your development workflow. Boost your productivity, code with confidence, and optimize your development process!

**It supports all languages!**

---

</div>

![How it works](https://raw.githubusercontent.com/Codium-ai/codiumai-jetbrains-release/main/media/docs/JB0.5.22.gif)

_Beta Version - Supported in JetBrains version 2023.1 and up_

## Features

#### 🤖 Generate unit tests suite automatically

#### 🔬 Analyze your code

#### 💡 Suggest code modifications to improve the performance and correctness of your code

#### 💫 Find potential bugs in your code and suggest ways to fix them

#### 👀 Prepare better for your PR

#### 💬 Free chat with GPT model with or without the code as context

#### 🚀 Help you improve code quality

By creating comprehensive test suites, our tool helps you catch and fix bugs early and ensures that your code is reliable and maintainable.

---

> #### TL;DR:

> - Click on the `Generate Tests` button above a function/class/method name
> - Use Codiumate PR-Assistant chat to prepare for your PR (Pro💎)

## How to use Codiumate?

#### Generate tests 
Generate tests for a function, a class, or a method using the `CodiumAI: Test this class/function/method` button above a function/class/method name:

![](https://raw.githubusercontent.com/Codium-ai/codiumai-jetbrains-release/main/media/docs/GenerateTests.png)

#### Review the results
Codiumate tab will present the test results - review the test names, objectives, types, and the test code:

![](https://raw.githubusercontent.com/Codium-ai/codiumai-jetbrains-release/main/media/docs/ReviewResults.png)

#### Explore behavior coverage

Codiumate generates a behavior list of your code and marks each behavior as covered or not covered based on the generated test.
The number of covered behaviors calculates the coverage percentages.
You can refresh the coverage when you modify your test suite (add, remove, or modify tests):

![](https://raw.githubusercontent.com/Codium-ai/codiumai-jetbrains-release/main/media/docs/BehaviorCoverage.png)

#### Add test for uncovered behavior

For behaviors that are not covered by tests, you can click on the `Generate test` button next to it, and Codiumate will generate a test
for this behavior.

![](https://raw.githubusercontent.com/Codium-ai/codiumai-jetbrains-release/main/media/docs/AddTestForBehavior.png)

#### Add more behaviors

Missing a behavior? Simply add new behaviors and generate tests for them:

![](https://raw.githubusercontent.com/Codium-ai/codiumai-jetbrains-release/main/media/docs/AddBehavior.png)

#### Modify tests
Want to modify a single test code? Simply type the change you want inside the `Suggest changes..` field, and TestGPT will modify the code based on your request:

![](https://raw.githubusercontent.com/Codium-ai/codiumai-jetbrains-release/main/media/docs/SuggestChanges.png)

You can also just click the `Regenerate` button and get an alternative code for this test:

![](https://raw.githubusercontent.com/Codium-ai/codiumai-jetbrains-release/main/media/docs/RegenerateSingleTest.png)

Want more tests? Click on `Give me more tests` at the bottom of the test suite:

![](https://raw.githubusercontent.com/Codium-ai/codiumai-jetbrains-release/main/media/docs/RequestMoreTests.png)

Want to remove a test from your test suite? Click on the `delete` button on each test:

![](https://raw.githubusercontent.com/Codium-ai/codiumai-jetbrains-release/main/media/docs/DeleteSingleTest.png)

#### Change test suite configurations
Improve and personalize your test suite by giving general instructions, examples of input and tests and select your preferred testing framework in the `Configuration` section:

![](https://raw.githubusercontent.com/Codium-ai/codiumai-jetbrains-release/main/media/docs/AddTestExample.png)
![](https://raw.githubusercontent.com/Codium-ai/codiumai-jetbrains-release/main/media/docs/ChangeGeneralConfiguration.png)
![](https://raw.githubusercontent.com/Codium-ai/codiumai-jetbrains-release/main/media/docs/ModifyFramework.png)

#### Save your test suite
When you're happy with your generated test suite, you can click on copy icon and copy the test suite code, or simply click on `Save to file` and we will create a test file for you:

![](https://raw.githubusercontent.com/Codium-ai/codiumai-jetbrains-release/main/media/docs/OpenCopy.png)

#### Code analysis
Read your code analysis written by our TestGPT model. You can use it for documentation and to make sure your code is doing what it should. Click on the `Code Analysis` tab and find out:

![](https://raw.githubusercontent.com/Codium-ai/codiumai-jetbrains-release/main/media/docs/CodeAnalysis.png)

#### Code suggestions

Our TestGPT model can find some insights about your code and suggests some modifications you can apply to your code (to improve performance, correctness, and more). Click on the `Code Suggestions` tab and find out:

![](https://raw.githubusercontent.com/Codium-ai/codiumai-jetbrains-release/main/media/docs/CodeSuggestions.png)

Choose the suggestion you want to apply, and merge them into your code:

![](https://raw.githubusercontent.com/Codium-ai/codiumai-jetbrains-release/main/media/docs/MergeSuggestions.png)

## Copy request ID

When reporting a bug, please copy the request ID and attach it to the bug report:

![](https://raw.githubusercontent.com/Codium-ai/codiumai-jetbrains-release/main/media/docs/RequestID.png)


## How to uninstall

1. Go to Preferences -> Plugins and select Codiumate from the list of enabled plugins.
2. Disable or uninstall the plugin using the dropdown below the name.

## Links

[![Join our Discord community](https://raw.githubusercontent.com/Codium-ai/codiumai-vscode-release/main/media/docs/Joincommunity.png)](https://discord.gg/kG35uSHDBc)

- Discord community: https://discord.gg/kG35uSHDBc
- CodiumAI site: https://codium.ai
- Blog: https://www.codium.ai/blog/
- Troubleshooting: https://www.codium.ai/blog/technical-faq-and-troubleshooting/
- Support: support@codium.ai

## Terms of use

- Terms of use: https://www.codium.ai/terms
- Privacy policy: https://www.codium.ai/privacy-policy
- Please notice - similar to other popular generative-AI tools (such as copilot), we also transmit code snippets to our servers.

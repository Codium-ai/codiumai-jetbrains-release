<div align="center">

# CodiumAI - Meaningful tests for busy devs

[![Discord](https://badgen.net/badge/icon/discord?icon=discord&label&color=purple)](https://discord.gg/kG35uSHDBc)

---

**CodiumAI** analyzes your code and generates meaningful tests to catch bugs before you ship. With CodiumAI, you can easily and quickly create comprehensive test suites that help you ensure the reliability and correctness of your software. Supports Python, Javascript and Typescript.

---

</div>

![How it works](https://raw.githubusercontent.com/Codium-ai/codiumai-jetbrains-release/main/media/docs/JB0.5.22.gif)

_Beta Version - Supported in PyCharm version 2022.1 and up, and in any other JetBrains IDE with Python, JavaScript or TypeScript support installed_

## Features

#### 🤖 Generates unit tests suite automatically

#### 🔬 Analyzes your code

#### 💡 Suggests code modifications to improve the performance and correctness of your code

#### 🚀 Helps you improve code quality

By creating comprehensive test suites, our tool helps you catch and fix bugs early and ensures that your code is reliable and maintainable.

---

## Supported languages

![](https://raw.githubusercontent.com/Codium-ai/codiumai-vscode-release/main/media/docs/supported.png)

---

> #### TL;DR:

> - Click on the `Generate Tests` button above a function/class/method name
> - Use CodiumAI quick actions left panel to generate tests

## How to use CodiumAI?

#### Generate tests 
Generate tests for a function, a class, or a method using the `CodiumAI: Test this class/function/method` button above a function/class/method name:

![](https://raw.githubusercontent.com/Codium-ai/codiumai-jetbrains-release/main/media/docs/GenerateTests.png)

#### Review the results
CodiumAI tab will present the test results - review the test names, objectives, types, and the test code:

![](https://raw.githubusercontent.com/Codium-ai/codiumai-jetbrains-release/main/media/docs/ReviewResults.png)

#### Generate tests from CodiumAI Panel

You can also view all the components you can generate tests for from CodiumAI left panel:

![](https://raw.githubusercontent.com/Codium-ai/codiumai-jetbrains-release/main/media/docs/QuickActions-Tests.png)

#### Explore behavior coverage

CodiumAI generates a behavior list of your code and marks each behavior as covered or not covered based on the generated test.
The number of covered behaviors calculates the coverage percentages.
You can refresh the coverage when you modify your test suite (add, remove, or modify tests):

![](https://raw.githubusercontent.com/Codium-ai/codiumai-jetbrains-release/main/media/docs/BehaviorCoverage.png)

#### Add test for uncovered behavior

For behaviors that are not covered by tests, you can click on the `Generate test` button next to it, and CodiumAI will generate a test
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

## How to uninstall

1. Go to Preferences -> Plugins and select CodiumAI from the list of enabled plugins.
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

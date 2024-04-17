# OS-Copilot: Towards Generalist Computer Agents with Self-Improvement

<div align="center">

<!-- [[PDF]](https://arxiv.org/pdf/2402.07456.pdf)
[[Documentation]](https://os-copilot.readthedocs.io/en/latest/) -->

[![Website](https://img.shields.io/website?url=https://os-copilot.github.io/)](https://os-copilot.github.io/)
[![PDF](https://img.shields.io/badge/pdf--blue)](https://arxiv.org/pdf/2402.07456.pdf)
[![Documentation](https://img.shields.io/badge/documentation--blue)](https://os-copilot.readthedocs.io/en/latest/)

![Python](https://img.shields.io/badge/python-3.10-blue)
[![Discord](https://img.shields.io/discord/1222168244673314847?logo=discord&style=flat)](https://discord.com/invite/rXS2XbgfaD)
[![Twitter](https://img.shields.io/twitter/url/https/twitter.com/cloudposse.svg?style=social&label=Follow%20%40oscopilot)](https://twitter.com/oscopilot)



<p align="center">
  <img src='pic/demo.png' width="100%">
</p>

</div>

<!-- ## 📖 Overview

- **OS-Copilot** is a pioneering conceptual framework for building generalist computer agents on Linux and MacOS, which provides a unified interface for app interactions in the heterogeneous OS ecosystem.
  
<p align="center">
  <img src='pic/framework.png' width="75%">
</p>
- Leveraging OS-Copilot, we built **FRIDAY**, a self-improving AI assistant capable of solving general computer tasks.

<p align="center">
  <img src='pic/FRIDAY.png' width="75%">
</p> -->

## 🔥 News
- *2024.3*: 🎉 OS-Copilot is accepted at the [LLM Agents Workshop](https://llmagents.github.io/)@ICLR 2024. 

## What is OS-Copilot

OS-Copilot is an open-source library to build generalist agents capable of automatically interfacing with comprehensive elements in an operating system (OS), including the web, code terminals, files, multimedia, and various third-party applications.

## ⚡️ Quickstart

1. **Clone the GitHub Repository:** 

   ```
   git clone https://github.com/OS-Copilot/OS-Copilot.git
   ```

2. **Set Up Python Environment and Install Dependencies:** 

   ```
   conda create -n oscopilot_env python=3.10 -y
   conda activate oscopilot_env
   
   cd OS-Copilot
   pip install -e .
   ```

4. **Set OpenAI API Key:** Configure your OpenAI API key in [.env](.env).
    ```
   cp .env_template .env
   ```

5. **Now you are ready to have fun:**
   ```
   python quick_start.py
   ```

\* **FRIDAY currently only supports single-round conversation**.

## 🛠️ Tutorial

| **Level**        | **Tutorial**                                                                                    | **Description**                                                                                            |
|------------------|-------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| **Beginner**     | [Installation](https://os-copilot.readthedocs.io/en/latest/installation.html)| Explore three methods to install FRIDAY.                                                                   |
| **Beginner**     | [Getting Started](https://os-copilot.readthedocs.io/en/latest/quick_start.html)| The simplest demonstration of FRIDAY with a quick_start.py script.                                         |
| **Intermediate** | [Adding Your Tools](https://os-copilot.readthedocs.io/en/latest/tutorials/add_tool.html)| Adding and removing tools to the FRIDAY.                                                                   |
| **Intermediate** | [Deploying API Services](https://os-copilot.readthedocs.io/en/latest/tutorials/deploy_api_service.html)| Demonstrate the deployment of API services for FRIDAY.                                                     |
| **Intermediate** | [Example: Automating Excel Tasks](https://os-copilot.readthedocs.io/en/latest/tutorials/example_excel.html)| Automating Excel control using FRIDAY.                                                                     |
| **Intermediate** | [Enhancing FRIDAY with Self-Learning for Excel Task Automation](https://os-copilot.readthedocs.io/en/latest/tutorials/self_learning.html) | Improved Excel control with self-directed learning.                                                        |
| **Advanced**     | [Designing New API Tools](https://os-copilot.readthedocs.io/en/latest/tutorials/design_new_api_tool.html)| Guides on deploying custom API tools for FRIDAY to extend its functionalities. |


<!-- ## 🛠️ FRIDAY-Gizmos
We maintain an open-source library of toolkits for FRIDAY, which includes tools that can be directly utilized within FRIDAY.
For a detailed list of tools, please see [FRIDAY-Gizmos](https://github.com/OS-Copilot/FRIDAY-Gizmos). The usage methods are as follows:

1. Find the tool you want to use in [FRIDAY-Gizmos](https://github.com/OS-Copilot/FRIDAY-Gizmos) and download its tool code.
2. Add the tool to FRIDAY's toolkit:
```shell
python friday/tool_repository/manager/tool_manager.py --add --tool_name [tool_name] --tool_path [tool_path]
```
3. If you wish to remove a tool, you can run:
```shell
python friday/tool_repository/manager/tool_manager.py --delete --tool_name [tool_name]
```

## 💻 User Interface (UI)

**Enhance Your Experience with Our Intuitive Frontend!** This interface is crafted for effortless control of your agents. For more details, visit [FRIDAY Frontend](https://github.com/OS-Copilot/FRIDAY-front).

## ✨ Deploy API Services

For comprehensive guidelines on deploying API services, please refer to the [OS-Copilot documentation](https://os-copilot.readthedocs.io/en/latest/).  -->

## 🏫 Community

Join our community to connect with other enthusiasts, researchers and developers:

- **[Discord](https://discord.com/invite/rXS2XbgfaD)**: Join our Discord server for real-time discussions and support.
- **[Twitter](https://twitter.com/oscopilot)**: Follow our Twitter to get latest new or tag us to share your demos!

## 👨‍💻‍ Contributing

**Visit [the roadmap](./docs/roadmap.md) to preview what the community is working on and become a contributor!**

<a href="https://github.com/OS-Copilot/OS-Copilot/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=OS-Copilot/OS-Copilot" />
</a>

<!-- Made with [contrib.rocks](https://contrib.rocks). -->

## 🛡 Disclaimer

OS-Copilot is provided "as is" without warranty of any kind. Users assume full responsibility for any risks associated with its use, including **potential data loss** or **changes to system settings**. The developers of OS-Copilot are not liable for any damages or losses resulting from its use. Users must ensure their actions comply with applicable laws and regulations.


## 🔎 Citation

```
@misc{wu2024oscopilot,
      title={OS-Copilot: Towards Generalist Computer Agents with Self-Improvement}, 
      author={Zhiyong Wu and Chengcheng Han and Zichen Ding and Zhenmin Weng and Zhoumianze Liu and Shunyu Yao and Tao Yu and Lingpeng Kong},
      year={2024},
      eprint={2402.07456},
      archivePrefix={arXiv},
      primaryClass={cs.AI}
}
```


## 📬 Contact

If you have any inquiries, suggestions, or wish to contact us for any reason, we warmly invite you to email us at wuzhiyong@pjlab.org.cn.
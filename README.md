<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><p align="center" dir="auto">
<a href="https://docs.jina.ai" rel="nofollow"><img src="https://github.com/jina-ai/jina/raw/master/docs/_static/logo-light.svg?raw=true" alt="Jina 徽标：通过云原生技术构建多模式人工智能服务·模型服务·生成式人工智能·神经搜索·云原生" width="150px" style="max-width: 100%;"></a>
</p>
<p align="center" dir="auto">
<b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用云原生技术构建多模式人工智能应用程序</font></font></b>
</p>
<p align="center" dir="auto">
<a href="https://pypi.org/project/jina/" rel="nofollow"><img alt="皮伊" src="https://camo.githubusercontent.com/a078e29226c42c320faec88867b127c881e704eb0bb664f62d43917d65a43c90/68747470733a2f2f696d672e736869656c64732e696f2f707970692f762f6a696e613f6c6162656c3d52656c65617365267374796c653d666c61742d737175617265" data-canonical-src="https://img.shields.io/pypi/v/jina?label=Release&amp;style=flat-square" style="max-width: 100%;"></a>

<a href="https://discord.jina.ai" rel="nofollow"><img src="https://camo.githubusercontent.com/19b2857e674e8e1f03f19117de15193bd38bd91e6bbbe67cbe5bebd73b26ef7c/68747470733a2f2f696d672e736869656c64732e696f2f646973636f72642f313130363534323232303131323330323133303f6c6f676f3d646973636f7264266c6f676f436f6c6f723d7768697465267374796c653d666c61742d737175617265" data-canonical-src="https://img.shields.io/discord/1106542220112302130?logo=discord&amp;logoColor=white&amp;style=flat-square" style="max-width: 100%;"></a>
<a href="https://pypistats.org/packages/jina" rel="nofollow"><img alt="PyPI - 从官方 pypistats 下载" src="https://camo.githubusercontent.com/9d8dcb016df632f69e0fd4b43f7f0005cb9f9b70931a3217be3ff6a2ceab54f1/68747470733a2f2f696d672e736869656c64732e696f2f707970692f646d2f6a696e613f7374796c653d666c61742d737175617265" data-canonical-src="https://img.shields.io/pypi/dm/jina?style=flat-square" style="max-width: 100%;"></a>
<a href="https://github.com/jina-ai/jina/actions/workflows/cd.yml"><img alt="Github CD 状态" src="https://github.com/jina-ai/jina/actions/workflows/cd.yml/badge.svg" style="max-width: 100%;"></a>
</p>

<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jina 允许您构建通过 gRPC、HTTP 和 WebSocket 进行通信的多模式</font></font><a href="#build-ai-models"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AI 服务</font></font></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="#build-a-pipeline"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">管道</font></font></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，然后对其进行扩展并部署到生产环境。您可以专注于逻辑和算法，而不必担心基础设施的复杂性。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/jina-ai/jina/blob/master/.github/images/build-deploy.png"><img src="/jina-ai/jina/raw/master/.github/images/build-deploy.png" alt="" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jina 为服务 ML 模型提供了流畅的 Python 体验，从本地部署过渡到 Docker-Compose、Kubernetes 或 Jina AI Cloud 等高级编排框架。 Jina 使每个开发人员都可以使用先进的解决方案工程和云原生技术。</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"></font><a href="https://docs.docarray.org/data_types/first_steps/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为任何数据类型</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和任何主流</font></font><a href="https://docarray.org/docarray/how_to/multimodal_training_and_serving/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">深度学习框架</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建模型并提供服务</font><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设计高性能服务，具有</font></font><a href="https://docs.jina.ai/concepts/orchestration/scale-out/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">轻松扩展</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、双工客户端-服务器流、批处理、</font></font><a href="https://docs.jina.ai/concepts/serving/executor/dynamic-batching/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">动态批处理</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、异步/非阻塞数据处理和任何</font></font><a href="https://docs.jina.ai/concepts/serving/gateway/#set-protocol-in-python" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">协议</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"></font><a href="https://github.com/jina-ai/jina#streaming-for-llms"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为LLM 模型</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提供服务，同时流式传输其输出</font><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过</font></font><a href="https://cloud.jina.ai" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Executor Hub</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、OpenTelemetry/Prometheus 可观察性集成 Docker 容器。</font></font></li>
<li><font style="vertical-align: inherit;"></font><a href="https://cloud.jina.ai" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过Jina AI Cloud</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">简化 CPU/GPU 托管</font><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"></font><a href="https://docs.jina.ai/cloud-nativeness/k8s/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过我们的Kubernetes</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://docs.jina.ai/cloud-nativeness/docker-compose/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Docker Compose</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">集成部署到您自己的云或系统</font><font style="vertical-align: inherit;">。</font></font></li>
</ul>
<details>
    <summary><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">等等，Jina 与 FastAPI 有什么不同？</font></font></strong></summary><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
Jina 的价值主张可能看起来与 FastAPI 非常相似。然而，有几个根本区别：
</font></font><p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据结构和通信协议</font></font></strong></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FastAPI 通信依赖于 Pydantic，Jina 依赖于</font></font><a href="https://github.com/docarray/docarray"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DocArray</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，允许 Jina 支持多种协议来公开其服务。对 gRPC 协议的支持对于数据密集型应用程序以及嵌入服务特别有用，其中嵌入和张量可以更有效地序列化。</font></font></li>
</ul>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">先进的编排和扩展能力</font></font></strong></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jina 允许您轻松容器化和编排您的服务和模型，从而提供并发性和可扩展性。</font></font></li>
<li>Jina lets you deploy applications formed from multiple microservices that can be containerized and scaled independently.</li>
</ul>
<p dir="auto"><strong>Journey to the cloud</strong></p>
<ul dir="auto">
<li>Jina provides a smooth transition from local development (using <a href="https://github.com/docarray/docarray">DocArray</a>) to local serving using <a href="https://docs.jina.ai/concepts/orchestration/deployment/" rel="nofollow">Deployment</a> and <a href="https://docs.jina.ai/concepts/orchestration/flow/" rel="nofollow">Flow</a>
to having production-ready services by using Kubernetes capacity to orchestrate the lifetime of containers.</li>
<li>By using <a href="https://cloud.jina.ai" rel="nofollow">Jina AI Cloud</a> you have access to scalable and serverless deployments of your applications in one command.</li>
</ul>
</details>

<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><a href="https://docs.jina.ai" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></a></h2><a id="user-content-documentation" class="anchor" aria-label="永久链接：文档" href="#documentation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></h2><a id="user-content-install" class="anchor" aria-label="永久链接：安装" href="#install"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>pip install jina</pre><div class="zeroclipboard-container">
   
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://docs.jina.ai/get-started/install/apple-silicon-m1-m2/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在Apple Silicon</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> / </font></font><a href="https://docs.jina.ai/get-started/install/windows/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Windows</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上查找更多安装选项</font><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开始使用</font></font></h2><a id="user-content-get-started" class="anchor" aria-label="永久链接：开始" href="#get-started"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基本概念</font></font></h3><a id="user-content-basic-concepts" class="anchor" aria-label="永久链接：基本概念" href="#basic-concepts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jina 具有三个基本层：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据层：</font></font><a href="https://docarray.docs.org/" rel="nofollow"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BaseDoc</font></font></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://docarray.docs.org/" rel="nofollow"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DocList</font></font></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（来自</font></font><a href="https://github.com/docarray/docarray"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DocArray</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）是 Jina 中的输入/输出格式。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">服务层：</font></font><a href="https://docs.jina.ai/concepts/serving/executor/" rel="nofollow"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Executor</font></font></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是一个转换和处理文档的 Python 类。只需将您的模型包装到执行器中，您就可以让 Jina 为它们提供服务和扩展。</font></font><a href="https://docs.jina.ai/concepts/serving/gateway/" rel="nofollow"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">网关</font></font></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是确保连接流内所有执行器的服务。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">编排层：  </font></font><a href="https://docs.jina.ai/concepts/orchestration/deployment" rel="nofollow"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部署</font></font></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">服务于单个执行器，而</font></font><a href="https://docs.jina.ai/concepts/orchestration/flow/" rel="nofollow"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">流</font></font></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">服务于链接到管道中的执行器。</font></font></li>
</ul>
<p dir="auto"><a href="https://docs.jina.ai/concepts/preliminaries/#" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此处解释了完整的术语表</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">服务AI模型</font></font></h3><a id="user-content-serve-ai-models" class="anchor" aria-label="永久链接：服务人工智能模型" href="#serve-ai-models"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>

<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">让我们构建一个快速、可靠且可扩展的基于 gRPC 的 AI 服务。在 Jina 中，我们称之为</font></font><strong><a href="https://docs.jina.ai/concepts/serving/executor/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Executor</font></font></a></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。我们简单的执行器将包装</font><font style="vertical-align: inherit;">Stability AI 的</font></font><a href="https://huggingface.co/stabilityai/stablelm-base-alpha-3b" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">StableLM</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> LLM。然后我们将使用</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Deployment</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来为其提供服务。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/jina-ai/jina/blob/master/.github/images/deployment-diagram.png"><img src="/jina-ai/jina/raw/master/.github/images/deployment-diagram.png" alt="" style="max-width: 100%;"></a></p>
<blockquote>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注意</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
一个 Deployment 仅服务于一个 Executor。要将多个 Executor 组合到一个管道中并为其提供服务，请使用</font></font><a href="#build-a-pipeline"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Flow</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
</blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">让我们实现服务的逻辑：</font></font></p>
<table>
<tbody><tr>
<th><code>executor.py</code></th> 
</tr><tr>
<td>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">from</span> <span class="pl-s1">jina</span> <span class="pl-k">import</span> <span class="pl-v">Executor</span>, <span class="pl-s1">requests</span>
<span class="pl-k">from</span> <span class="pl-s1">docarray</span> <span class="pl-k">import</span> <span class="pl-v">DocList</span>, <span class="pl-v">BaseDoc</span>

<span class="pl-k">from</span> <span class="pl-s1">transformers</span> <span class="pl-k">import</span> <span class="pl-s1">pipeline</span>


<span class="pl-k">class</span> <span class="pl-v">Prompt</span>(<span class="pl-v">BaseDoc</span>):
    <span class="pl-s1">text</span>: <span class="pl-s1">str</span>


<span class="pl-k">class</span> <span class="pl-v">Generation</span>(<span class="pl-v">BaseDoc</span>):
    <span class="pl-s1">prompt</span>: <span class="pl-s1">str</span>
    <span class="pl-s1">text</span>: <span class="pl-s1">str</span>


<span class="pl-k">class</span> <span class="pl-v">StableLM</span>(<span class="pl-v">Executor</span>):
    <span class="pl-k">def</span> <span class="pl-en">__init__</span>(<span class="pl-s1">self</span>, <span class="pl-c1">**</span><span class="pl-s1">kwargs</span>):
        <span class="pl-en">super</span>().<span class="pl-en">__init__</span>(<span class="pl-c1">**</span><span class="pl-s1">kwargs</span>)
        <span class="pl-s1">self</span>.<span class="pl-s1">generator</span> <span class="pl-c1">=</span> <span class="pl-en">pipeline</span>(
            <span class="pl-s">'text-generation'</span>, <span class="pl-s1">model</span><span class="pl-c1">=</span><span class="pl-s">'stabilityai/stablelm-base-alpha-3b'</span>
        )

    <span class="pl-en">@<span class="pl-s1">requests</span></span>
    <span class="pl-k">def</span> <span class="pl-en">generate</span>(<span class="pl-s1">self</span>, <span class="pl-s1">docs</span>: <span class="pl-v">DocList</span>[<span class="pl-v">Prompt</span>], <span class="pl-c1">**</span><span class="pl-s1">kwargs</span>) <span class="pl-c1">-&gt;</span> <span class="pl-v">DocList</span>[<span class="pl-v">Generation</span>]:
        <span class="pl-s1">generations</span> <span class="pl-c1">=</span> <span class="pl-v">DocList</span>[<span class="pl-v">Generation</span>]()
        <span class="pl-s1">prompts</span> <span class="pl-c1">=</span> <span class="pl-s1">docs</span>.<span class="pl-s1">text</span>
        <span class="pl-s1">llm_outputs</span> <span class="pl-c1">=</span> <span class="pl-s1">self</span>.<span class="pl-en">generator</span>(<span class="pl-s1">prompts</span>)
        <span class="pl-k">for</span> <span class="pl-s1">prompt</span>, <span class="pl-s1">output</span> <span class="pl-c1">in</span> <span class="pl-en">zip</span>(<span class="pl-s1">prompts</span>, <span class="pl-s1">llm_outputs</span>):
            <span class="pl-s1">generations</span>.<span class="pl-en">append</span>(<span class="pl-v">Generation</span>(<span class="pl-s1">prompt</span><span class="pl-c1">=</span><span class="pl-s1">prompt</span>, <span class="pl-s1">text</span><span class="pl-c1">=</span><span class="pl-s1">output</span>))
        <span class="pl-k">return</span> <span class="pl-s1">generations</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="from jina import Executor, requests
from docarray import DocList, BaseDoc

from transformers import pipeline


class Prompt(BaseDoc):
    text: str


class Generation(BaseDoc):
    prompt: str
    text: str


class StableLM(Executor):
    def __init__(self, **kwargs):
        super().__init__(**kwargs)
        self.generator = pipeline(
            'text-generation', model='stabilityai/stablelm-base-alpha-3b'
        )

    @requests
    def generate(self, docs: DocList[Prompt], **kwargs) -> DocList[Generation]:
        generations = DocList[Generation]()
        prompts = docs.text
        llm_outputs = self.generator(prompts)
        for prompt, output in zip(prompts, llm_outputs):
            generations.append(Generation(prompt=prompt, text=output))
        return generations" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</td>
</tr>
</tbody></table>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后我们使用 Python API 或 YAML 部署它：</font></font></p>
<div dir="auto">
<table>
<tbody><tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Python API：</font></font><code>deployment.py</code> </th> 
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">yaml：</font></font><code>deployment.yml</code> </th>
</tr>
<tr>
<td>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">from</span> <span class="pl-s1">jina</span> <span class="pl-k">import</span> <span class="pl-v">Deployment</span>
<span class="pl-k">from</span> <span class="pl-s1">executor</span> <span class="pl-k">import</span> <span class="pl-v">StableLM</span>

<span class="pl-s1">dep</span> <span class="pl-c1">=</span> <span class="pl-v">Deployment</span>(<span class="pl-s1">uses</span><span class="pl-c1">=</span><span class="pl-v">StableLM</span>, <span class="pl-s1">timeout_ready</span><span class="pl-c1">=</span><span class="pl-c1">-</span><span class="pl-c1">1</span>, <span class="pl-s1">port</span><span class="pl-c1">=</span><span class="pl-c1">12345</span>)

<span class="pl-k">with</span> <span class="pl-s1">dep</span>:
    <span class="pl-s1">dep</span>.<span class="pl-en">block</span>()</pre><div class="zeroclipboard-container">
   
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</td>
<td>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">jtype</span>: <span class="pl-s">Deployment</span>
<span class="pl-ent">with</span>:
  <span class="pl-ent">uses</span>: <span class="pl-s">StableLM</span>
  <span class="pl-ent">py_modules</span>:
    - <span class="pl-s">executor.py</span>
  <span class="pl-ent">timeout_ready</span>: <span class="pl-c1">-1</span>
  <span class="pl-ent">port</span>: <span class="pl-c1">12345</span></pre><div class="zeroclipboard-container">
   
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">并使用 CLI 运行 YAML 部署：</font></font><code>jina deployment --uses deployment.yml</code></p>
</td>
</tr>
</tbody></table>
</div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用</font></font><a href="https://docs.jina.ai/concepts/client/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jina Client</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">向服务发出请求：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">from</span> <span class="pl-s1">jina</span> <span class="pl-k">import</span> <span class="pl-v">Client</span>
<span class="pl-k">from</span> <span class="pl-s1">docarray</span> <span class="pl-k">import</span> <span class="pl-v">DocList</span>, <span class="pl-v">BaseDoc</span>


<span class="pl-k">class</span> <span class="pl-v">Prompt</span>(<span class="pl-v">BaseDoc</span>):
    <span class="pl-s1">text</span>: <span class="pl-s1">str</span>


<span class="pl-k">class</span> <span class="pl-v">Generation</span>(<span class="pl-v">BaseDoc</span>):
    <span class="pl-s1">prompt</span>: <span class="pl-s1">str</span>
    <span class="pl-s1">text</span>: <span class="pl-s1">str</span>


<span class="pl-s1">prompt</span> <span class="pl-c1">=</span> <span class="pl-v">Prompt</span>(
    <span class="pl-s1">text</span><span class="pl-c1">=</span><span class="pl-s">'suggest an interesting image generation prompt for a mona lisa variant'</span>
)

<span class="pl-s1">client</span> <span class="pl-c1">=</span> <span class="pl-v">Client</span>(<span class="pl-s1">port</span><span class="pl-c1">=</span><span class="pl-c1">12345</span>)  <span class="pl-c"># use port from output above</span>
<span class="pl-s1">response</span> <span class="pl-c1">=</span> <span class="pl-s1">client</span>.<span class="pl-en">post</span>(<span class="pl-s1">on</span><span class="pl-c1">=</span><span class="pl-s">'/'</span>, <span class="pl-s1">inputs</span><span class="pl-c1">=</span>[<span class="pl-s1">prompt</span>], <span class="pl-s1">return_type</span><span class="pl-c1">=</span><span class="pl-v">DocList</span>[<span class="pl-v">Generation</span>])

<span class="pl-en">print</span>(<span class="pl-s1">response</span>[<span class="pl-c1">0</span>].<span class="pl-s1">text</span>)</pre><div class="zeroclipboard-container">
 
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre lang="text" class="notranslate"><code>a steampunk version of the Mona Lisa, incorporating mechanical gears, brass elements, and Victorian era clothing details
</code></pre><div class="zeroclipboard-container">
   
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>

<blockquote>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注意</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
在笔记本中，您不能使用客户端</font></font><code>deployment.block()</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后向客户端发出请求。请参阅上面的 Colab 链接，获取可重现的 Jupyter Notebook 代码片段。</font></font></p>
</blockquote>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">建立管道</font></font></h3><a id="user-content-build-a-pipeline" class="anchor" aria-label="永久链接：建立管道" href="#build-a-pipeline"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>

<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有时您希望将微服务链接到管道中。这就是</font></font><a href="https://docs.jina.ai/concepts/orchestration/flow/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Flow 的</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用武之地。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Flow是一个</font></font><a href="https://en.wikipedia.org/wiki/Directed_acyclic_graph" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DAG</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">管道，由一组步骤组成，它编排一组</font></font><a href="https://docs.jina.ai/concepts/serving/executor/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Executor</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和一个</font></font><a href="https://docs.jina.ai/concepts/serving/gateway/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Gateway</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来提供端到端服务。</font></font></p>
<blockquote>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注意</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
如果您只想为单个 Executor 提供服务，则可以使用</font></font><a href="#build-ai--ml-services"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Deployment</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
</blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例如，让我们将</font></font><a href="#build-ai--ml-services"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">StableLM 语言模型</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与稳定扩散图像生成模型结合起来。将这些服务链接到一个</font></font><a href="https://docs.jina.ai/concepts/orchestration/flow/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Flow</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中将为我们提供一项服务，该服务将根据 LLM 生成的提示生成图像。</font></font></p>
<table>
<tbody><tr>
<th><code>text_to_image.py</code></th> 
</tr><tr>
<td>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">import</span> <span class="pl-s1">numpy</span> <span class="pl-k">as</span> <span class="pl-s1">np</span>
<span class="pl-k">from</span> <span class="pl-s1">jina</span> <span class="pl-k">import</span> <span class="pl-v">Executor</span>, <span class="pl-s1">requests</span>
<span class="pl-k">from</span> <span class="pl-s1">docarray</span> <span class="pl-k">import</span> <span class="pl-v">BaseDoc</span>, <span class="pl-v">DocList</span>
<span class="pl-k">from</span> <span class="pl-s1">docarray</span>.<span class="pl-s1">documents</span> <span class="pl-k">import</span> <span class="pl-v">ImageDoc</span>


<span class="pl-k">class</span> <span class="pl-v">Generation</span>(<span class="pl-v">BaseDoc</span>):
    <span class="pl-s1">prompt</span>: <span class="pl-s1">str</span>
    <span class="pl-s1">text</span>: <span class="pl-s1">str</span>


<span class="pl-k">class</span> <span class="pl-v">TextToImage</span>(<span class="pl-v">Executor</span>):
    <span class="pl-k">def</span> <span class="pl-en">__init__</span>(<span class="pl-s1">self</span>, <span class="pl-c1">**</span><span class="pl-s1">kwargs</span>):
        <span class="pl-en">super</span>().<span class="pl-en">__init__</span>(<span class="pl-c1">**</span><span class="pl-s1">kwargs</span>)
        <span class="pl-k">from</span> <span class="pl-s1">diffusers</span> <span class="pl-k">import</span> <span class="pl-v">StableDiffusionPipeline</span>
        <span class="pl-k">import</span> <span class="pl-s1">torch</span>

        <span class="pl-s1">self</span>.<span class="pl-s1">pipe</span> <span class="pl-c1">=</span> <span class="pl-v">StableDiffusionPipeline</span>.<span class="pl-en">from_pretrained</span>(
            <span class="pl-s">"CompVis/stable-diffusion-v1-4"</span>, <span class="pl-s1">torch_dtype</span><span class="pl-c1">=</span><span class="pl-s1">torch</span>.<span class="pl-s1">float16</span>
        ).<span class="pl-en">to</span>(<span class="pl-s">"cuda"</span>)

    <span class="pl-en">@<span class="pl-s1">requests</span></span>
    <span class="pl-k">def</span> <span class="pl-en">generate_image</span>(<span class="pl-s1">self</span>, <span class="pl-s1">docs</span>: <span class="pl-v">DocList</span>[<span class="pl-v">Generation</span>], <span class="pl-c1">**</span><span class="pl-s1">kwargs</span>) <span class="pl-c1">-&gt;</span> <span class="pl-v">DocList</span>[<span class="pl-v">ImageDoc</span>]:
        <span class="pl-s1">result</span> <span class="pl-c1">=</span> <span class="pl-v">DocList</span>[<span class="pl-v">ImageDoc</span>]()
        <span class="pl-s1">images</span> <span class="pl-c1">=</span> <span class="pl-s1">self</span>.<span class="pl-en">pipe</span>(
            <span class="pl-s1">docs</span>.<span class="pl-s1">text</span>
        ).<span class="pl-s1">images</span>  <span class="pl-c"># image here is in [PIL format](https://pillow.readthedocs.io/en/stable/)</span>
        <span class="pl-s1">result</span>.<span class="pl-s1">tensor</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">array</span>(<span class="pl-s1">images</span>)
        <span class="pl-k">return</span> <span class="pl-s1">result</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="import numpy as np
from jina import Executor, requests
from docarray import BaseDoc, DocList
from docarray.documents import ImageDoc


class Generation(BaseDoc):
    prompt: str
    text: str


class TextToImage(Executor):
    def __init__(self, **kwargs):
        super().__init__(**kwargs)
        from diffusers import StableDiffusionPipeline
        import torch

        self.pipe = StableDiffusionPipeline.from_pretrained(
            &quot;CompVis/stable-diffusion-v1-4&quot;, torch_dtype=torch.float16
        ).to(&quot;cuda&quot;)

    @requests
    def generate_image(self, docs: DocList[Generation], **kwargs) -> DocList[ImageDoc]:
        result = DocList[ImageDoc]()
        images = self.pipe(
            docs.text
        ).images  # image here is in [PIL format](https://pillow.readthedocs.io/en/stable/)
        result.tensor = np.array(images)
        return result" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</td>
</tr>
</tbody></table>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/jina-ai/jina/blob/master/.github/images/flow-diagram.png"><img src="/jina-ai/jina/raw/master/.github/images/flow-diagram.png" alt="" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Python 或 YAML 构建流程：</font></font></p>
<div dir="auto">
<table>
<tbody><tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Python API：</font></font><code>flow.py</code> </th> 
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">yaml：</font></font><code>flow.yml</code> </th>
</tr>
<tr>
<td>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">from</span> <span class="pl-s1">jina</span> <span class="pl-k">import</span> <span class="pl-v">Flow</span>
<span class="pl-k">from</span> <span class="pl-s1">executor</span> <span class="pl-k">import</span> <span class="pl-v">StableLM</span>
<span class="pl-k">from</span> <span class="pl-s1">text_to_image</span> <span class="pl-k">import</span> <span class="pl-v">TextToImage</span>

<span class="pl-s1">flow</span> <span class="pl-c1">=</span> (
    <span class="pl-v">Flow</span>(<span class="pl-s1">port</span><span class="pl-c1">=</span><span class="pl-c1">12345</span>)
    .<span class="pl-en">add</span>(<span class="pl-s1">uses</span><span class="pl-c1">=</span><span class="pl-v">StableLM</span>, <span class="pl-s1">timeout_ready</span><span class="pl-c1">=</span><span class="pl-c1">-</span><span class="pl-c1">1</span>)
    .<span class="pl-en">add</span>(<span class="pl-s1">uses</span><span class="pl-c1">=</span><span class="pl-v">TextToImage</span>, <span class="pl-s1">timeout_ready</span><span class="pl-c1">=</span><span class="pl-c1">-</span><span class="pl-c1">1</span>)
)

<span class="pl-k">with</span> <span class="pl-s1">flow</span>:
    <span class="pl-s1">flow</span>.<span class="pl-en">block</span>()</pre><div class="zeroclipboard-container">
    
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</td>
<td>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">jtype</span>: <span class="pl-s">Flow</span>
<span class="pl-ent">with</span>:
    <span class="pl-ent">port</span>: <span class="pl-c1">12345</span>
<span class="pl-ent">executors</span>:
  - <span class="pl-ent">uses</span>: <span class="pl-s">StableLM</span>
    <span class="pl-ent">timeout_ready</span>: <span class="pl-c1">-1</span>
    <span class="pl-ent">py_modules</span>:
      - <span class="pl-s">executor.py</span>
  - <span class="pl-ent">uses</span>: <span class="pl-s">TextToImage</span>
    <span class="pl-ent">timeout_ready</span>: <span class="pl-c1">-1</span>
    <span class="pl-ent">py_modules</span>:
      - <span class="pl-s">text_to_image.py</span></pre><div class="zeroclipboard-container">
   
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后使用 CLI 运行 YAML 流程：</font></font><code>jina flow --uses flow.yml</code></p>
</td>
</tr>
</tbody></table>
</div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后，使用</font></font><a href="https://docs.jina.ai/concepts/client/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jina Client</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">向 Flow 发出请求：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">from</span> <span class="pl-s1">jina</span> <span class="pl-k">import</span> <span class="pl-v">Client</span>
<span class="pl-k">from</span> <span class="pl-s1">docarray</span> <span class="pl-k">import</span> <span class="pl-v">DocList</span>, <span class="pl-v">BaseDoc</span>
<span class="pl-k">from</span> <span class="pl-s1">docarray</span>.<span class="pl-s1">documents</span> <span class="pl-k">import</span> <span class="pl-v">ImageDoc</span>


<span class="pl-k">class</span> <span class="pl-v">Prompt</span>(<span class="pl-v">BaseDoc</span>):
    <span class="pl-s1">text</span>: <span class="pl-s1">str</span>


<span class="pl-s1">prompt</span> <span class="pl-c1">=</span> <span class="pl-v">Prompt</span>(
    <span class="pl-s1">text</span><span class="pl-c1">=</span><span class="pl-s">'suggest an interesting image generation prompt for a mona lisa variant'</span>
)

<span class="pl-s1">client</span> <span class="pl-c1">=</span> <span class="pl-v">Client</span>(<span class="pl-s1">port</span><span class="pl-c1">=</span><span class="pl-c1">12345</span>)  <span class="pl-c"># use port from output above</span>
<span class="pl-s1">response</span> <span class="pl-c1">=</span> <span class="pl-s1">client</span>.<span class="pl-en">post</span>(<span class="pl-s1">on</span><span class="pl-c1">=</span><span class="pl-s">'/'</span>, <span class="pl-s1">inputs</span><span class="pl-c1">=</span>[<span class="pl-s1">prompt</span>], <span class="pl-s1">return_type</span><span class="pl-c1">=</span><span class="pl-v">DocList</span>[<span class="pl-v">ImageDoc</span>])

<span class="pl-s1">response</span>[<span class="pl-c1">0</span>].<span class="pl-en">display</span>()</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="from jina import Client
from docarray import DocList, BaseDoc
from docarray.documents import ImageDoc


class Prompt(BaseDoc):
    text: str


prompt = Prompt(
    text='suggest an interesting image generation prompt for a mona lisa variant'
)

client = Client(port=12345)  # use port from output above
response = client.post(on='/', inputs=[prompt], return_type=DocList[ImageDoc])

response[0].display()" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/jina-ai/jina/blob/master/.github/images/mona-lisa.png"><img src="/jina-ai/jina/raw/master/.github/images/mona-lisa.png" alt="" style="max-width: 100%;"></a></p>

<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">轻松的可扩展性和并发性</font></font></h3><a id="user-content-easy-scalability-and-concurrency" class="anchor" aria-label="永久链接：轻松的可扩展性和并发性" href="#easy-scalability-and-concurrency"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为什么不直接使用标准 Python 来构建该服务和管道呢？ Jina 通过提高应用程序的可扩展性和云原生能力来加快应用程序的上市时间。 Jina 还处理生产和其他 Day-2 操作中的基础设施复杂性，以便您可以专注于数据应用程序本身。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过开箱即用的可扩展性功能（例如</font></font><a href="https://docs.jina.ai/concepts/orchestration/scale-out/#replicate-executors" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">副本</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://docs.jina.ai/concepts/orchestration/scale-out/#customize-polling-behaviors" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分片</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://docs.jina.ai/concepts/serving/executor/dynamic-batching/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">动态批处理）</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提高应用程序的吞吐量。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">让我们通过副本和动态批处理来扩展稳定扩散执行器部署：</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/jina-ai/jina/blob/master/.github/images/scaled-deployment.png"><img src="/jina-ai/jina/raw/master/.github/images/scaled-deployment.png" alt="" style="max-width: 100%;"></a></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">创建两个副本，并</font></font><a href="https://docs.jina.ai/concepts/orchestration/scale-out/#replicate-on-multiple-gpus" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为每个副本分配一个 GPU</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">启用动态批处理以处理传入的并行请求以及相同的模型推理。</font></font></li>
</ul>
<div dir="auto">
<table>
<tbody><tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">正常部署</font></font></th> 
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">规模化部署</font></font></th>
</tr>
<tr>
<td>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">jtype</span>: <span class="pl-s">Deployment</span>
<span class="pl-ent">with</span>:
  <span class="pl-ent">uses</span>: <span class="pl-s">TextToImage</span>
  <span class="pl-ent">timeout_ready</span>: <span class="pl-c1">-1</span>
  <span class="pl-ent">py_modules</span>:
    - <span class="pl-s">text_to_image.py</span></pre><div class="zeroclipboard-container">
   
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</td>
<td>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">jtype</span>: <span class="pl-s">Deployment</span>
<span class="pl-ent">with</span>:
  <span class="pl-ent">uses</span>: <span class="pl-s">TextToImage</span>
  <span class="pl-ent">timeout_ready</span>: <span class="pl-c1">-1</span>
  <span class="pl-ent">py_modules</span>:
    - <span class="pl-s">text_to_image.py</span>
  <span class="pl-ent">env</span>:
   <span class="pl-ent">CUDA_VISIBLE_DEVICES</span>: <span class="pl-s">RR</span>
  <span class="pl-ent">replicas</span>: <span class="pl-c1">2</span>
  <span class="pl-ent">uses_dynamic_batching</span>: <span class="pl-c"><span class="pl-c">#</span> configure dynamic batching</span>
    <span class="pl-ent">/default</span>:
      <span class="pl-ent">preferred_batch_size</span>: <span class="pl-c1">10</span>
      <span class="pl-ent">timeout</span>: <span class="pl-c1">200</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="jtype: Deployment
with:
  uses: TextToImage
  timeout_ready: -1
  py_modules:
    - text_to_image.py
  env:
   CUDA_VISIBLE_DEVICES: RR
  replicas: 2
  uses_dynamic_batching: # configure dynamic batching
    /default:
      preferred_batch_size: 10
      timeout: 200" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</td>
</tr>
</tbody></table>
</div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">假设您的计算机有两个 GPU，与正常部署相比，使用扩展部署 YAML 将提供更好的吞吐量。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这些功能适用于</font></font><a href="https://docs.jina.ai/concepts/orchestration/yaml-spec/#example-yaml" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Deployment YAML</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://docs.jina.ai/concepts/orchestration/yaml-spec/#example-yaml" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Flow YAML</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。借助 YAML 语法，无论执行器代码如何，您都可以注入部署配置。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部署到云端</font></font></h2><a id="user-content-deploy-to-the-cloud" class="anchor" aria-label="永久链接：部署到云端" href="#deploy-to-the-cloud"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将您的执行器容器化</font></font></h3><a id="user-content-containerize-your-executor" class="anchor" aria-label="永久链接：容器化您的执行器" href="#containerize-your-executor"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为了将您的解决方案部署到云中，您需要对您的服务进行容器化。 Jina 提供了</font></font><a href="https://docs.jina.ai/concepts/serving/executor/hub/create-hub-executor/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Executor Hub</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，这是一个完美的工具，可以简化这个过程，为您省去很多麻烦。它还允许您公开或私下共享这些执行程序。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您只需在文件夹中构建您的执行器：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>TextToImage/
├── executor.py
├── config.yml
├── requirements.txt</pre><div class="zeroclipboard-container">
   
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div dir="auto">
<table>
<tbody><tr>
<th> <code>config.yml</code> </th>
<th> <code>requirements.txt</code> </th>
</tr>
<tr>
<td>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">jtype</span>: <span class="pl-s">TextToImage</span>
<span class="pl-ent">py_modules</span>:
  - <span class="pl-s">executor.py</span>
<span class="pl-ent">metas</span>:
  <span class="pl-ent">name</span>: <span class="pl-s">TextToImage</span>
  <span class="pl-ent">description</span>: <span class="pl-s">Text to Image generation Executor based on StableDiffusion</span>
  <span class="pl-ent">url</span>:
  <span class="pl-ent">keywords</span>: <span class="pl-s">[]</span></pre><div class="zeroclipboard-container">
 
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</td>
<td>
<div class="highlight highlight-text-adblock notranslate position-relative overflow-auto" dir="auto"><pre>diffusers
accelerate
transformers</pre><div class="zeroclipboard-container">
    
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</td>
</tr>
</tbody></table>
</div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后通过执行以下操作将执行器推送到集线器</font></font><code>jina hub push TextToImage</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这将为您提供一个可在您的</font></font><code>Deployment</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">并</font></font><code>Flow</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用推送的 Executors 容器中使用的 URL。</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">jtype</span>: <span class="pl-s">Flow</span>
<span class="pl-ent">with</span>:
    <span class="pl-ent">port</span>: <span class="pl-c1">12345</span>
<span class="pl-ent">executors</span>:
  - <span class="pl-ent">uses</span>: <span class="pl-s">jinai+docker://&lt;user-id&gt;/StableLM</span>
  - <span class="pl-ent">uses</span>: <span class="pl-s">jinai+docker://&lt;user-id&gt;/TextToImage</span></pre><div class="zeroclipboard-container">
  
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">踏上云原生快车道</font></font></h3><a id="user-content-get-on-the-fast-lane-to-cloud-native" class="anchor" aria-label="永久链接：踏上云原生的快车道" href="#get-on-the-fast-lane-to-cloud-native"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将 Kubernetes 与 Jina 结合使用非常简单：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>jina <span class="pl-k">export</span> kubernetes flow.yml ./my-k8s
kubectl apply -R -f my-k8s</pre><div class="zeroclipboard-container">
   
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Docker Compose 也是如此：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>jina <span class="pl-k">export</span> docker-compose flow.yml docker-compose.yml
docker-compose up</pre><div class="zeroclipboard-container">
   
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<blockquote>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注意</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
您还可以将 Deployment YAML 导出到</font></font><a href="https://docs.jina.ai/concepts/serving/executor/serve/#serve-via-kubernetes" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kubernetes</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://docs.jina.ai/concepts/serving/executor/serve/#serve-via-docker-compose" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Docker Compose</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
</blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">那不是全部。我们还支持</font></font><a href="https://docs.jina.ai/cloud-nativeness/opentelemetry/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenTelemetry、Prometheus 和 Jaeger</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">哪些云原生技术仍然对您构成挑战？</font></font><a href="https://github.com/jina-ai/jina/issues"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">告诉我们</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，我们将处理复杂性并让您轻松完成。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部署到JCloud</font></font></h3><a id="user-content-deploy-to-jcloud" class="anchor" aria-label="永久链接：部署到 JCloud" href="#deploy-to-jcloud"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您还可以将 Flow 部署到 JCloud，在这里您可以通过单个命令轻松享受自动缩放、监控等功能。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">首先，</font><font style="vertical-align: inherit;">通过指定资源要求并使用容器化的 Hub Executors将</font></font><code>flow.yml</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件转换为与</font></font><a href="https://docs.jina.ai/yaml-spec/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JCloud 兼容的 YAML 。</font></font></a><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后，使用</font></font><code>jina cloud deploy</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">命令部署到云端：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>wget https://raw.githubusercontent.com/jina-ai/jina/master/.github/getting-started/jcloud-flow.yml
jina cloud deploy jcloud-flow.yml</pre><div class="zeroclipboard-container">
  
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<blockquote>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">警告</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">完成本教程后，请确保删除/清理流程，以节省资源和积分。</font></font></p>
</blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">阅读有关</font></font><a href="https://docs.jina.ai/concepts/jcloud/#deploy" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将 Flows 部署到 JCloud 的</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更多信息。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LLM 流媒体</font></font></h3><a id="user-content-streaming-for-llms" class="anchor" aria-label="永久链接：法学硕士流媒体" href="#streaming-for-llms"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>

<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">大型语言模型可以为从聊天机器人到助手和智能系统的各种应用程序提供支持。然而，这些模型可能又重又慢，而您的用户希望系统既智能</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">又</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">快速！</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">大型语言模型的工作原理是将您的问题转化为令牌，然后一次生成一个新令牌，直到它决定停止生成为止。这意味着您希望将</font><font style="vertical-align: inherit;">大型语言模型生成的输出标记</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">流式传输</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">到客户端。在本教程中，我们将讨论如何使用 Jina 中的流端点来实现这一目标。</font></font></p>

<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">服务模式</font></font></h4><a id="user-content-service-schemas" class="anchor" aria-label="永久链接：服务模式" href="#service-schemas"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>

<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">第一步是定义流服务架构，就像在任何其他服务框架中所做的那样。服务的输入是提示和要生成的最大令牌数，而输出只是令牌 ID：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">from</span> <span class="pl-s1">docarray</span> <span class="pl-k">import</span> <span class="pl-v">BaseDoc</span>


<span class="pl-k">class</span> <span class="pl-v">PromptDocument</span>(<span class="pl-v">BaseDoc</span>):
    <span class="pl-s1">prompt</span>: <span class="pl-s1">str</span>
    <span class="pl-s1">max_tokens</span>: <span class="pl-s1">int</span>


<span class="pl-k">class</span> <span class="pl-v">ModelOutputDocument</span>(<span class="pl-v">BaseDoc</span>):
    <span class="pl-s1">token_id</span>: <span class="pl-s1">int</span>
    <span class="pl-s1">generated_text</span>: <span class="pl-s1">str</span></pre><div class="zeroclipboard-container">
    
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>

<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">服务初始化</font></font></h4><a id="user-content-service-initialization" class="anchor" aria-label="永久链接：服务初始化" href="#service-initialization"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>

<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们的服务依赖于一个大的语言模型。作为示例，我们将使用该</font></font><code>gpt2</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型。这就是您在执行器中加载此类模型的方式</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">from</span> <span class="pl-s1">jina</span> <span class="pl-k">import</span> <span class="pl-v">Executor</span>, <span class="pl-s1">requests</span>
<span class="pl-k">from</span> <span class="pl-s1">transformers</span> <span class="pl-k">import</span> <span class="pl-v">GPT2Tokenizer</span>, <span class="pl-v">GPT2LMHeadModel</span>
<span class="pl-k">import</span> <span class="pl-s1">torch</span>

<span class="pl-s1">tokenizer</span> <span class="pl-c1">=</span> <span class="pl-v">GPT2Tokenizer</span>.<span class="pl-en">from_pretrained</span>(<span class="pl-s">'gpt2'</span>)


<span class="pl-k">class</span> <span class="pl-v">TokenStreamingExecutor</span>(<span class="pl-v">Executor</span>):
    <span class="pl-k">def</span> <span class="pl-en">__init__</span>(<span class="pl-s1">self</span>, <span class="pl-c1">**</span><span class="pl-s1">kwargs</span>):
        <span class="pl-en">super</span>().<span class="pl-en">__init__</span>(<span class="pl-c1">**</span><span class="pl-s1">kwargs</span>)
        <span class="pl-s1">self</span>.<span class="pl-s1">model</span> <span class="pl-c1">=</span> <span class="pl-v">GPT2LMHeadModel</span>.<span class="pl-en">from_pretrained</span>(<span class="pl-s">'gpt2'</span>)</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="from jina import Executor, requests
from transformers import GPT2Tokenizer, GPT2LMHeadModel
import torch

tokenizer = GPT2Tokenizer.from_pretrained('gpt2')


class TokenStreamingExecutor(Executor):
    def __init__(self, **kwargs):
        super().__init__(**kwargs)
        self.model = GPT2LMHeadModel.from_pretrained('gpt2')" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>

<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实现流端点</font></font></h4><a id="user-content-implement-the-streaming-endpoint" class="anchor" aria-label="永久链接：实现流端点" href="#implement-the-streaming-endpoint"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>

<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们的流端点接受 a</font></font><code>PromptDocument</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">作为输入并流</font></font><code>ModelOutputDocument</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">s。要将文档流式传输回客户端，请</font></font><code>yield</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在端点实现中使用关键字。因此，我们使用该模型生成最多</font></font><code>max_tokens</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">token 并生成它们，直到生成停止：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">class</span> <span class="pl-v">TokenStreamingExecutor</span>(<span class="pl-v">Executor</span>):
    ...

    <span class="pl-en">@<span class="pl-en">requests</span>(<span class="pl-s1">on</span><span class="pl-c1">=</span><span class="pl-s">'/stream'</span>)</span>
    <span class="pl-k">async</span> <span class="pl-k">def</span> <span class="pl-en">task</span>(<span class="pl-s1">self</span>, <span class="pl-s1">doc</span>: <span class="pl-v">PromptDocument</span>, <span class="pl-c1">**</span><span class="pl-s1">kwargs</span>) <span class="pl-c1">-&gt;</span> <span class="pl-v">ModelOutputDocument</span>:
        <span class="pl-s1">input</span> <span class="pl-c1">=</span> <span class="pl-en">tokenizer</span>(<span class="pl-s1">doc</span>.<span class="pl-s1">prompt</span>, <span class="pl-s1">return_tensors</span><span class="pl-c1">=</span><span class="pl-s">'pt'</span>)
        <span class="pl-s1">input_len</span> <span class="pl-c1">=</span> <span class="pl-s1">input</span>[<span class="pl-s">'input_ids'</span>].<span class="pl-s1">shape</span>[<span class="pl-c1">1</span>]
        <span class="pl-k">for</span> <span class="pl-s1">_</span> <span class="pl-c1">in</span> <span class="pl-en">range</span>(<span class="pl-s1">doc</span>.<span class="pl-s1">max_tokens</span>):
            <span class="pl-s1">output</span> <span class="pl-c1">=</span> <span class="pl-s1">self</span>.<span class="pl-s1">model</span>.<span class="pl-en">generate</span>(<span class="pl-c1">**</span><span class="pl-s1">input</span>, <span class="pl-s1">max_new_tokens</span><span class="pl-c1">=</span><span class="pl-c1">1</span>)
            <span class="pl-k">if</span> <span class="pl-s1">output</span>[<span class="pl-c1">0</span>][<span class="pl-c1">-</span><span class="pl-c1">1</span>] <span class="pl-c1">==</span> <span class="pl-s1">tokenizer</span>.<span class="pl-s1">eos_token_id</span>:
                <span class="pl-k">break</span>
            <span class="pl-k">yield</span> <span class="pl-v">ModelOutputDocument</span>(
                <span class="pl-s1">token_id</span><span class="pl-c1">=</span><span class="pl-s1">output</span>[<span class="pl-c1">0</span>][<span class="pl-c1">-</span><span class="pl-c1">1</span>],
                <span class="pl-s1">generated_text</span><span class="pl-c1">=</span><span class="pl-s1">tokenizer</span>.<span class="pl-en">decode</span>(
                    <span class="pl-s1">output</span>[<span class="pl-c1">0</span>][<span class="pl-s1">input_len</span>:], <span class="pl-s1">skip_special_tokens</span><span class="pl-c1">=</span><span class="pl-c1">True</span>
                ),
            )
            <span class="pl-s1">input</span> <span class="pl-c1">=</span> {
                <span class="pl-s">'input_ids'</span>: <span class="pl-s1">output</span>,
                <span class="pl-s">'attention_mask'</span>: <span class="pl-s1">torch</span>.<span class="pl-en">ones</span>(<span class="pl-c1">1</span>, <span class="pl-en">len</span>(<span class="pl-s1">output</span>[<span class="pl-c1">0</span>])),
            }</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="class TokenStreamingExecutor(Executor):
    ...

    @requests(on='/stream')
    async def task(self, doc: PromptDocument, **kwargs) -> ModelOutputDocument:
        input = tokenizer(doc.prompt, return_tensors='pt')
        input_len = input['input_ids'].shape[1]
        for _ in range(doc.max_tokens):
            output = self.model.generate(**input, max_new_tokens=1)
            if output[0][-1] == tokenizer.eos_token_id:
                break
            yield ModelOutputDocument(
                token_id=output[0][-1],
                generated_text=tokenizer.decode(
                    output[0][input_len:], skip_special_tokens=True
                ),
            )
            input = {
                'input_ids': output,
                'attention_mask': torch.ones(1, len(output[0])),
            }" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从文档中</font><font style="vertical-align: inherit;">了解有关</font></font><a href="https://docs.jina.ai/concepts/serving/executor/add-endpoints/#streaming-endpoints" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">流式传输端点的</font></font></a><font style="vertical-align: inherit;"></font><code>Executor</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更多信息。</font></font></p>

<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">服务并发送请求</font></font></h4><a id="user-content-serve-and-send-requests" class="anchor" aria-label="永久链接：服务并发送请求" href="#serve-and-send-requests"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>

<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">最后一步是为执行器提供服务并使用客户端发送请求。使用 gRPC 为 Executor 提供服务：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">from</span> <span class="pl-s1">jina</span> <span class="pl-k">import</span> <span class="pl-v">Deployment</span>

<span class="pl-k">with</span> <span class="pl-v">Deployment</span>(<span class="pl-s1">uses</span><span class="pl-c1">=</span><span class="pl-v">TokenStreamingExecutor</span>, <span class="pl-s1">port</span><span class="pl-c1">=</span><span class="pl-c1">12345</span>, <span class="pl-s1">protocol</span><span class="pl-c1">=</span><span class="pl-s">'grpc'</span>) <span class="pl-k">as</span> <span class="pl-s1">dep</span>:
    <span class="pl-s1">dep</span>.<span class="pl-en">block</span>()</pre><div class="zeroclipboard-container">
  
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发送来自客户端的请求：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">import</span> <span class="pl-s1">asyncio</span>
<span class="pl-k">from</span> <span class="pl-s1">jina</span> <span class="pl-k">import</span> <span class="pl-v">Client</span>


<span class="pl-k">async</span> <span class="pl-k">def</span> <span class="pl-en">main</span>():
    <span class="pl-s1">client</span> <span class="pl-c1">=</span> <span class="pl-v">Client</span>(<span class="pl-s1">port</span><span class="pl-c1">=</span><span class="pl-c1">12345</span>, <span class="pl-s1">protocol</span><span class="pl-c1">=</span><span class="pl-s">'grpc'</span>, <span class="pl-s1">asyncio</span><span class="pl-c1">=</span><span class="pl-c1">True</span>)
    <span class="pl-k">async</span> <span class="pl-k">for</span> <span class="pl-s1">doc</span> <span class="pl-c1">in</span> <span class="pl-s1">client</span>.<span class="pl-en">stream_doc</span>(
        <span class="pl-s1">on</span><span class="pl-c1">=</span><span class="pl-s">'/stream'</span>,
        <span class="pl-s1">inputs</span><span class="pl-c1">=</span><span class="pl-v">PromptDocument</span>(<span class="pl-s1">prompt</span><span class="pl-c1">=</span><span class="pl-s">'what is the capital of France ?'</span>, <span class="pl-s1">max_tokens</span><span class="pl-c1">=</span><span class="pl-c1">10</span>),
        <span class="pl-s1">return_type</span><span class="pl-c1">=</span><span class="pl-v">ModelOutputDocument</span>,
    ):
        <span class="pl-en">print</span>(<span class="pl-s1">doc</span>.<span class="pl-s1">generated_text</span>)


<span class="pl-s1">asyncio</span>.<span class="pl-en">run</span>(<span class="pl-en">main</span>())</pre><div class="zeroclipboard-container">
   
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre lang="text" class="notranslate"><code>The
The capital
The capital of
The capital of France
The capital of France is
The capital of France is Paris
The capital of France is Paris.
</code></pre><div class="zeroclipboard-container">
   
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>


<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持</font></font></h2><a id="user-content-support" class="anchor" aria-label="永久链接： 支持" href="#support"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">加入我们的</font></font><a href="https://discord.jina.ai" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Discord 社区</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，与其他社区成员讨论想法。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">订阅我们的</font></font><a href="https://youtube.com/c/jina-ai" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">YouTube 频道上的最新视频教程</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">加入我们</font></font></h2><a id="user-content-join-us" class="anchor" aria-label="永久链接：加入我们" href="#join-us"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://jina.ai" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jina 由Jina AI</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持</font><font style="vertical-align: inherit;">并在</font></font><a href="/jina-ai/jina/blob/master/LICENSE"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Apache-2.0</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下获得许可。</font></font></p>

</article></div>

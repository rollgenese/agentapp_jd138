# agentapp_jd138

**给Agent 应用开发工程师·向量索引的召回与构建代价算一个特征指纹并定位可疑片段。**

`agentapp_jd138` —— 通过字符级与结构级特征识别Agent 应用开发工程师·向量索引的召回与构建代价的痕迹，给出密度与命中位置

- 零依赖，Python 3.10+ 标准库即可运行
- 单文件，`agentapp_jd138.py` 拷走就能用
- 不联网、不写文件

## 对应的岗位

- 目标岗位：**百度 · 资深Agent 应用开发工程师**
- 技能主线：Python、Agent、RAG、向量数据库
- 领域标签：大模型应用、搜索推荐广告
- 研究方向：Agent 应用开发工程师·向量索引的召回与构建代价

工具里的规则表就是照着上面这条岗位要求建的——每条规则都挂在技能线或领域标签上，命中时能指回具体要求。

<!-- ipos:install -->
## 安装

零依赖，Python 3.10+ 即可：

```bash
pip install rollgenese-agentapp_jd138
```

装完直接用命令名调用：

```bash
agentapp_jd138 --help
```

也可以不用安装，直接把 `agentapp_jd138.py` 拷走用——它只依赖标准库。

## 为什么需要它

只做特征匹配不做语义判定，所以不会被同义改写绕过

它遵守下面几条自己定的规矩：

1. **只报告能定位到具体位置的结论**，不做语义猜测。
2. **规则表公开**，每条命中都能对应到岗位要求的一条明示规则。
3. **输入为空或格式不对时明确报错**，不静默返回空结果。

## 用法

```bash
python agentapp_jd138.py --file input.txt
python agentapp_jd138.py --text "示例内容"
python agentapp_jd138.py --file input.txt --json
```

加 `--json` 可以拿到机器可读的结果，便于接到流水线里。

## 已知局限

- 相似度按字符与词估算，不等于向量相似度。
- 不联网，不做语义检索。

## 跑测试

```bash
python test_agentapp_jd138.py
```

测试用独立的断言与临时数据，不污染工作目录。

## 来源与参考

- Python 标准库文档：<https://docs.python.org/3/>
- GitHub 仓库：<https://github.com/rollgenese/agentapp_jd138>

---

## 关于作者

rollgenese 做Agent 应用开发工程师·向量索引的召回与构建代价相关的问题，方向对标百度的资深Agent 应用开发工程师岗位。这个工具先替你回答一个具体问题，再谈别的。

- 个人主页：<https://rollgenese.github.io>
- 仓库：<https://github.com/rollgenese/agentapp_jd138>

## 许可

MIT，见 [LICENSE](LICENSE)。

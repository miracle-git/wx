## 运行步骤

- 首先全局安装json-server
```bash
npm install -g json-server
```
- 在项目根目录下进去mock目录并启动json-server
```bash
cd mock
json-server --watch --port 8888 all.json (这里也可以换成)
```
- 然后会依次提示您输入项目名称，描述，作者等信息（不输入将采用默认值）
- 选择项目类型为**wx**，回车开始下载项目模板
- 当出现**项目创建成功**表示项目脚手架已下载成功
- 按照操作指引安装依赖，运行项目即可

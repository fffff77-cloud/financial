# financial
“用于构建和优化一个小型金融知识图谱，涵盖数据收集、处理、存储和查询。”
# 小型金融知识图谱

##  项目简介
本项目用于构建一个小型的金融知识图谱，涵盖数据收集、处理、存储和查询。目标是构建一个易于扩展和查询的金融数据知识库。

##  功能
- 数据收集（新闻、公告、财务数据）
- 实体识别与关系抽取
- 知识图谱存储（Neo4j / RDF）
- 可视化查询

## 使用方法
```bash
git clone https://github.com/你的用户名/financial-knowledge-graph.git
cd financial-knowledge-graph
pip install -r requirements.txt  # 安装依赖
python main.py  # 运行主程序
---

### **2. 创建 .gitignore**
如果你的项目包含 Python 代码，可以添加 `.gitignore`，避免提交不必要的文件：
```bash
echo "__pycache__/" >> .gitignore
echo ".DS_Store" >> .gitignore
echo "venv/" >> .gitignore
git add .gitignore
git commit -m "添加 gitignore"
git push origin main

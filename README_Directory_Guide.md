# PROFI-Version Directory Guide

## 📁 目录说明

这个目录包含Milano Moda Maison eBay项目的HTML模板和相关资源。

### 🎯 主要文件

#### 1. 核心模板文件
- **`Minimalist_Standard_EXTERNE_CSS_v2.95.html`** - 主HTML模板
  - 这是所有eBay产品的基础模板
  - 修改此文件会影响所有产品的设计
  - 包含完整的HTML结构、CSS样式和JavaScript功能

#### 2. 样式文件
- **`minimalist_style.css`** - 原始CSS样式文件
  - 包含所有样式定义
  - 字体引用和布局规则
  - 响应式设计代码

#### 3. 字体资源
- **`fonts/`** - 字体文件目录
  - 包含Cardo、FontAwesome、Lato等字体
  - 支持多种格式：.woff, .woff2, .ttf, .eot
  - 确保模板在所有浏览器中正确显示

#### 4. 产品样本
- **`Real_Product_Samples_Final/`** - 最终产品HTML样本
  - 包含50个真实产品的HTML预览文件
  - 用于验证模板效果
  - 包含index.html浏览页面

#### 5. 文档
- **`Wichtige Informationen (LiesMich ReadMe).pdf`** - 原作者说明文档
- **`docs`** - 项目文档文件
- **`README_Directory_Guide.md`** - 本说明文件

### 🔧 使用方法

#### 修改模板设计
1. **编辑主模板**：
   ```bash
   open "Minimalist_Standard_EXTERNE_CSS_v2.95.html"
   ```

2. **预览修改效果**：
   ```bash
   cd /Users/yinxianzhi/workspace/listing
   python3 scripts/create_design_preview.py
   ```

3. **应用到所有产品**：
   ```bash
   python3 scripts/apply_template_modifications.py
   ```

#### 查看产品样本
- 打开 `Real_Product_Samples_Final/index.html` 查看所有产品
- 或直接打开任意产品HTML文件查看单个产品效果

### ⚠️ 重要注意事项

1. **备份保护**
   - 修改前会自动创建备份文件
   - 备份文件格式：`*.backup_[timestamp]`
   - 只保留最新的备份文件

2. **占位符保护**
   - 不要删除图片占位符：`https://placehold.it/800`
   - 不要删除文本占位符区域
   - 保持HTML结构完整

3. **字体依赖**
   - `fonts/` 目录包含所有必需字体
   - 删除字体文件会影响显示效果
   - 字体通过GitHub Pages CDN提供在线访问

### 📊 目录统计

- **清理时间**: 2025-09-08 11:47:46
- **主模板**: 1个文件 (~40KB)
- **字体文件**: ~130个文件
- **产品样本**: 50个HTML文件 + 1个索引
- **文档文件**: 多个说明文档

### 🔗 相关链接

- **GitHub Pages CDN**: https://trivesa.github.io/ebay-fonts-cdn/
- **项目文档**: /Users/yinxianzhi/workspace/listing/docs/
- **工具脚本**: /Users/yinxianzhi/workspace/listing/scripts/

---

*本指南由Milano Moda Maison eBay项目自动生成*
*更新时间: 2025-09-08 11:47:46*

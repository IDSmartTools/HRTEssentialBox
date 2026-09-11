**100% Free: This plugin is permanently free. Any individual or organization is welcome to use it for free. Selling or commercial distribution is strictly prohibited.**

**Compatibility: Supports Adobe InDesign 2020 and newer versions.**

**Important Notice:**

**Certain plugin features/effects may be lost after saving as or exporting to an IDML file.**

**Documents created with this plugin may lose their effects when opened in an InDesign environment where this plugin is not installed. Please double-check your work before exporting or sharing.**

**Feedback & Support: If you encounter any issues or bugs, please feel free to report them via the contact details located at the bottom of the plugin interface.**

**Support the Developer: If you find this plugin helpful, donations/tips are greatly appreciated! Your support will motivate me to keep updating and improving the tool!**



**完全免费：本插件永久免费，任何机构或个人均可免费使用，严禁任何形式的售卖或商业转售。**

**版本兼容：插件支持 Adobe InDesign 2020 及更新版本。**

**注意事项（重要提醒）：**

**部分插件功能在保存/导出为 IDML 格式后，相关效果可能会丢失。**

**使用本插件制作的效果，在未安装本插件的 InDesign 中打开时，可能会丢失效果。请在输出或交付前做好确认。**

**问题反馈：如在使用过程中遇到问题或发现 Bug，可以通过插件界面下方的联系方式向我反馈。**

**支持与打赏：如果您觉得这个插件对您有所帮助，欢迎打赏支持！您的鼓励是我持续维护和更新的最大动力！**

# Object-Related Functions
## 1.1 Single-Page Display (Right-Click Shortcut)
Maintains the left-right positioning of spread elements but arranges them in a single-page layout. This is primarily used to prevent inner bleed from crossing over to the opposite page.
## 1.2 Remove Objects Outside Page (Right-Click Shortcut)
Deletes all objects located outside the page boundaries.
## 1.3 Duplicate Objects
Allows duplicating objects across the entire document. The duplicated objects can be positioned with incremental spacing and offsets to create a dynamic effect.
## 1.4 Cross-Spread Duplication
Unlike the previous function which duplicates a fixed number of times, this feature calculates the interval automatically based on start and end points. By defining the start point, end point, and the object to duplicate, it automatically calculates the spacing between them and places one object per spread according to that interval, ultimately achieving a flip-book animation effect. (Note: You can also achieve this using the standard duplication function by pre-calculating the quantity and spacing.)
## 1.5 Circular Array
Evenly distributes copies of an object around a circle based on a specified quantity.
## 1.6 Batch Move Objects
When pages are added or deleted, many objects may shift collectively. Use this tool to adjust their positions in bulk.
## 1.7 Add Anchor Point
Adds a new anchor point between two existing Bézier corner points.
## 1.8 Align Objects to Node
Select multiple objects and set one as the key object. The remaining objects will sequentially align their centers to the nodes of the key object.
## 1.9 Align Objects by Points
Aligns and arranges objects based solely on nine reference points, ignoring their width and height dimensions.
## 1.10 Pie Chart
Quickly generates pie charts based on numerical data.
## 1.11 Batch Process Objects
Batch-processes objects sharing similar attributes based on a reference object.

# Text-Related Functions
## 2.1 Clear Leading/Trailing Whitespace (Right-Click Shortcut)
Removes all whitespace characters (spaces, line breaks, etc.) before and after paragraphs. This conforms to typographic standards and is my most frequently used plugin feature. Parameters can be configured to remove specific special characters, such as empty placeholders from data merging.
## 2.2 Fit Text Frame Width to Content (Right-Click Shortcut)
Adjusts the width of selected text frames to fit the text content. Particularly useful for repositioning multi-line short text.
## 2.3 Thread Text Frames (Right-Click Shortcut)
Threads selected text frames in top-to-bottom order, inserting paragraph returns between the text content.
## 2.4 Unthread All Text Frames (Right-Click Shortcut)
Breaks all threaded text frames within the selection into independent, unlinked text frames.
## 2.5 Unthread From Here (Right-Click Shortcut)
Disconnects the selected text frame from the preceding threaded frames. Especially useful for magazine layouts or when starting new chapters in books.
## 2.6 Remove Empty Frames (Right-Click Shortcut)
Removes all empty text frames within the selected threading chain.
## 2.7 Create Threaded Text Frames (Right-Click Shortcut)
When applied to one or more threaded text frames, this function places identical threaded text frames at the same position on every page from the current page to the end of the document. These frames remain linked throughout. Combined with paragraph styles, this is ideal for creating calendars.
## 2.8 Adjust Overset Text Frames (Right-Click Shortcut)
Automatically resizes overset text frames by expanding them. Particularly helpful for adjusting text frames after data merging.
## 2.9 Split Text by Paragraph (Right-Click Shortcut)
Separates selected text into individual text frames by paragraph. Ideal for preparing captions for illustrations or charts.
## 2.10 Footnote Conversion Tool
Offers five conversion modes: Text to Footnote, Footnote to Text, Text to Anchored Object, Anchored Object to Footnote, and Footnote to Anchored Object. Useful for restructuring fixed-format text into different presentations. For example, easily converts parenthetical text in articles into proper footnotes.
## 2.11 Character Pattern Masking
Select multiple objects and a text frame (set as the key object). Characters intersecting with the objects will have their appearance modified based on those objects—great for creating text effects.
## 2.12 Link-Marked Text Frames
Text frames marked with a purple "LINK" tag are threaded in top-to-bottom order; only the first frame is retained while the rest are deleted. Designed for data merging workflows where all text frames need to be consolidated into a single thread.
## 2.13 Clear Style Overrides
Clears overrides for Paragraph Styles, Character Styles, Table Styles, Cell Styles, and Object Styles. Multiple style types can be selected at once. Can also be accessed via right-click directly from the Styles panel after selecting a style.
## 2.14 Chinese Numerals
Inserts traditional Chinese counting numerals for page numbers, footnotes, paragraph numbering, etc. Unlike InDesign’s built-in Chinese numbering (which renders "10" as "一〇"), this feature uses the standard form "十". Fully compatible with export.
## 2.15 Character Transformation
Applies gradient or random transformations to selected characters based on predefined rules.
## 2.16 Image-Filled Text
Applies image colors as fill within text characters.
## 2.17 Foreground/Background Glyph Effects
Adds a highlighter-style effect to text.

# Table+
The plugin includes a dedicated Table+ module. Although tables fall under text-related features, their complexity and scope warrant a separate section.
## 3.1 Extract Cell Text to Separate Frame (Right-Click Shortcut)
Copies text from selected cells into independent text frames.
## 3.2 Split Table by Row (Right-Click Shortcut)
Splits the table into two tables at the topmost row of the selected cell range.
## 3.3 Split Table by Column (Right-Click Shortcut)
Splits the table into two tables at the leftmost column of the selected cell range.
## 3.4 Transpose Table (Right-Click Shortcut)
Swaps rows and columns (row 1 becomes column 1, row 2 becomes column 2, etc.). Typically used when row/column counts differ significantly and layout space needs compression.
## 3.5 Reverse Table Direction (Right-Click Shortcut)
Reverses the table’s horizontal direction (a feature native to Middle Eastern versions of InDesign).
## 3.6 Insert Text Content into Cells (Right-Click Shortcut)
Inserts text into table cells. Select both the source text frame(s) and the target table frame (set as key object). The top-left corner of each source text frame must reside within the target cell. Multiple text frames inserted into a single cell are automatically separated by paragraph returns.
## 3.7 Continued Table Header
Automatically updates continued-table headers. Works by attaching an anchored object to the table; headers refresh automatically when text reflows.
## 3.8 Quick Match Rows
Applies cell styles and attributes to specified rows, with options to delete matched rows.
## 3.9 Quick Match Columns
Applies cell styles and attributes to specified columns, with options to delete matched columns.
## 3.10 Utility – Split Table
Batch-splits tables at empty rows or empty columns.
## 3.11 Utility – Auto-Fill
Fills empty rows or columns with content from adjacent upper or left cells.
## 3.12 Utility – Delete Duplicate Rows/Columns
Removes duplicate rows or columns, retaining only one instance. Changes total row/column count.
## 3.13 Utility – Separate Text and Table
Inserts a paragraph return between tables and adjacent text. Automatically invoked during "Clear Leading/Trailing Whitespace."
## 3.14 Utility – Unmerge Vertically Merged Cells
Batch-unmerges vertically merged cells.
## 3.15 Utility – Clear Duplicate Adjacent Items
Retains content only in the first of consecutive identical cells; subsequent duplicates are cleared. Row/column count remains unchanged.
## 3.16 Utility – Fill Empty Cells
Populates blank cells with specified content.
## 3.17 Utility – Collapse Rows
Compacts table layout by collapsing rows to save space.
## 3.18 Table Width Adjustment
Batch-adjusts table widths; quickly aligns table width to the containing text frame.
## 3.19 Batch Table Styling
Applies styles to multiple tables simultaneously.
## 3.20 Table Height Adjustment
Batch-adjusts table heights; useful for aligning table bottom edges to text frame bottoms.
## 3.21 Batch Place Excel Files
Imports multiple .xlsx files into InDesign, automatically trimming excess whitespace from each table.
## 3.22 Column Width Adjustment
Batch-adjusts column widths for tables with a specified number of columns using custom values.

# Drawing Tools
## 4.1 Sine/Cosine Curves
Generates sine and cosine waveforms.
## 4.2 Rosette Patterns
Creates rosette effects by bending periodic curves into folded patterns. Includes built-in cosine and triangular waveforms; custom curves can also be drawn.
## 4.3 Penrose tiling
Quickly draw complex Penrose tilings, including custom designs

# Global Utilities
## 5.1 Export Fonts
Exports all used fonts to a designated folder—especially valuable for non-open-source fonts. Automatically runs during package operations.
## 5.2 Convert Linked Images to TIFF
Converts linked images to TIFF format at a specified resolution. Bitmaps retain their original maximum resolution; vector graphics are rasterized at the user-defined resolution (recommend setting higher resolution for vectors).
## 5.3 Export Embedded/Hidden Links
Some images may have been pasted directly into InDesign from external sources, making future edits difficult. This utility converts such embedded images back into editable linked files. Particularly useful on Windows, where large images copied from Word can cause InDesign to freeze.

# 1. 对象相关功能
## 1.1 单页显示（右键快捷键）
将跨页保持左右位置不变，但是是单页排列。这样做的作用主要是针对内侧的出血不会跨越到另一侧。
## 1.2 移除页面外对象（右键快捷键）
将页面之外的对象全部删掉
## 1.3 复制对象
可以同时在全书范围内复制对象，复制的对象可以递增位置和间距，达到一个动态的效果。
## 1.4 跨页复制对象
与上一个的区别是，上一个复制确定的复制数量。用上一个功能计算好数量和间距可以实现这个复制的功能。
这个功能很简单，只做跨页间的复制，只要确定好起点、终点、复制的对象，就可以自动计算起点到终点间的间隔，每个跨页根据间隔放置一个对象。最后达到一个翻页动态效果。
## 1.5 圆周复制
根据数量直接平均分布复制一个对象。
## 1.6 批量移动对象
当增加或删除页面时，很多对象可能会整体偏移。用这个来调。
## 1.7 添加锚点
在两个贝塞尔角点之间添加一个新点。
## 1.8 对象对齐节点
同时选中多个对象，将节点对象设置为关键对象。剩余的对象会按照顺序依次将自己的中心对齐节点
## 1.9 按点排列对象
只根据九个点去排列对齐对象，不在乎宽度和高度。
## 1.10 饼状图
根据数值快速生成饼状图。
## 1.11 批量处理对象
根据基准对象批量处理相同特征的对象。
# 2. 文本相关功能
## 2.1 清除段落前后空白（右键快捷键）
将段落前后的空格回车等空白字符全部删除，这符合排版的标准，是我最常用的插件功能。
可以设置清除参数，将一些软件特有的特殊字符移除，比如数据合并的空占位符。
## 2.2 文本框宽度适合（右键快捷键）
选中的文本框根据文本宽度调整文本框的宽度。尤其适合多行短文本调整位置时使用。
## 2.3 串接文本框（右键快捷键）
选中的文本框按照自上而下的顺序串接起来，文本之间会插入回车换行。
## 2.4 断开全部文本框（右键快捷键）
会将选中的文本框所在的所有的流排文本框全部打散成独立文本框。
## 2.5 由此断开文本框（右键快捷键）
会将选中的文本框与前面流排文本框断开连接。尤其适合杂志排版、书籍换章时操作文本。
## 2.6 移除空白框架（右键快捷键）
会将选中的文本框所在的流排文本框中所有的空文本框移除。
## 2.7 创建串接文本框（右键快捷键）
选中一个或几个串接文本框运行这个功能，会从所在页开始直到文档最后一页，都会在同一位置放置相同的串接文本框，并且这些文本框都是相互串接的，从开始到文档最后一页。这个功能结合段落样式特别适合作日历。
## 2.8 溢流文本框调整（右键快捷键）
自动调整溢流文本框。就是简单的拉大文本框。特别适合数据合并之后的溢流文本框调整。
## 2.9 按段分离文本（右键快捷键）
将所选文本按照段落放置到单独的文本框。特别适合做插图、图表时使用。
## 2.10 脚注转换工具
提供5种转换方式。文本转脚注、脚注转文本、文本转定位对象、定位对象转脚注，脚注转定位对象。当一些固定结构的文本需要换一个呈现方式的时候，用这个功能会很方便。
文章中的一些括号文本需要转成对应的脚注，用这个功能轻松完成。
## 2.11 字符图案
同时选择多个对象和一个文本框，文本框需要被设置成关键对象，可以根据对象将与对象相交的文本改变字符演示，很适合做文本效果。
## 2.12 链接标记文本框
加入标记的文本框会出现紫色的“LINK”，链接标记文本框，会按照自上而下的顺序，先串接，之后只保留第一个文本框，其余会被删掉。这个功能是给数据合并设计的，有时候我需要将文本框全部串接起来。
## 2.13 清除样式覆盖
段落样式、字符样式、表样式、单元格样式、对象样式。五种样式清除覆盖，一次可选多个样式。也可以在样式面板中直接选择样式后，右键操作。
## 2.14 中文编号
页码、脚注、段落编号等位置加入中文计数编号。InDesign内置的编号，十表示为“一〇”，我加入的这个编号就是正常的“十”。可以正常导出。
## 2.15 字符变换
使选中的字符按照设置的规则进行渐变变化或者随机变化。
## 2.16 图片字符
将图片颜色印在文字上
## 2.17 前后景字形
给文字添加一个荧光笔的效果
# 3. Table+
插件内置Table+功能，虽然将表格列为文本一类，但是，表格的体量和复杂度都应该单独拎出来说一下。
## 3.1 按单元格分离文本（右键快捷键）
选中的单元格文本会单独复制到一个独立的文本框。
## 3.2 按行拆分表（右键快捷键）
表格会按照所单元格范围的最上方所在行拆分成两个表格。
## 3.3 按列拆分表（右键快捷键）
表格会按照所单元格范围的最左方所在列拆分成两个表格。
## 3.4 转置表格（右键快捷键）
表格行列会发生转换，第一行变为第一列，第二行变为第二列……这个功能一般用在行数与列数相差很大，排版空间需要压缩的时候用。
## 3.5 反转方向（右键快捷键）
这个是中东版本表格的功能，会反转表格左右方向。
## 3.6 文本内容插入单元格（右键快捷键）
文本插入单元格。选中插入的文本框和表格文本框，需要将表格文本框设为关键对象。要插入的文本框左上角需要在目标单元格内，注意只是文本框的左上角。多个文本框同时插入一个单元格，文本之间会自动添加回车换行。
## 3.7 续表功能
添加续表的表格，会自动更新。原理就是给表格添加一个定位对象。在文本变化之后，会自动更新续表。
## 3.8 快速匹配行
制定表格某几行的单元格样式，属性。是否删除
## 3.9 快速匹配列
制定表格某几列的单元格样式，属性。是否删除
## 3.10 小工具-拆分表
按照空行或者空列批量拆分表格
## 3.11 小工具-填充
会将空行或空列根据上面或左面的内容进行自动填充。
## 3.12 小工具-删除相同行/列
相同内容的行或者列会直接删除，只保留一个，表格的行列数量会改变
## 3.13 小工具-分隔文本和表格
在表格和文本间添加回车。这个功能在清空文本前后空白中会自动调用。
## 3.14 小工具-取消纵向合并
批量将表格纵向合并的单元格取消合并。
## 3.15 小工具-清空相同项
将相邻的相同内容的单元格，只保留第一个的内容，后面的单元格内容会清空。表格的行列数量不会改变
## 3.16 小工具-填充空白单元格
将给定内容填入空白的单元格
## 3.17 小工具-折叠行
可以节省空间使表格紧凑
## 3.18 表格宽度
批量修改表格宽度，可以快速将表格的宽度对齐到所在文本框。
## 3.19 批量操作表
批量给表格添加样式。
## 3.20 表格高度
批量调整表格高度。用这个功能可以将表格下边缘对齐文本框下边缘。
## 3.21 批量置入Excel
可以将多个xlsx表格文件置入到InDesign。自动修剪表格掉表格的空白部分。
## 3.22 表格列宽
可以将某个列数的表格的列宽按照自定的数值批量调整。
# 4. 绘制
## 4.1 正余弦
## 4.2 团花
可以将周期曲线弯曲折叠做成团花效果。内置余弦和三角曲线，其他曲线可以自己绘制。
## 4.3 彭罗斯密铺
快速绘制复杂的彭罗斯密铺图案，包括自定义

# 5. 全局
## 5.1 导出字体
将用到的字体导出到指定文件夹，这个功能对于非开源字体很有用。在执行打包操作的时候，会自动运行这个功能。
## 5.2 链接图转Tiff
将链接图转成制定空间的tiff文件，位图的分辨率最大不会超过原图的分辨率。对于矢量图最大分辨率就是制定的分辨率，使用的时候将制定分辨率调大一下。
## 5.3 导出隐藏链接
一些图片素材可能是随手从别处复制进InDesign的。这会导致后期没法修改。用这个功能可以将图片转成一般的可以编辑的素材。这在windows上很有用，一些word复制进InDesign的图片非常大，会让InDesign卡死。

# Changelog

## [0.0.3] - 2023-03-28
### Add
* 补充对 m_TextProcessingArray 数组的优化。

## [0.0.2] - 2023-03-26
### Fixed
- 修复了使用 Vertical Layout Group 来排版时，会出现 lineInfo 空引用的问题；
- 修复了 OverFlowMode 设置为 Ellipsis 的情况下，创建网格时 lineInfo 空引用的问题；
- 修复了使用 unicode \u00AD 来进行软换行时可能跟会导致的 lineInfo 空引用的问题。


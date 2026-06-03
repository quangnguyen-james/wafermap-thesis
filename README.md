# wafermap-thesis
Nghiên cứu ứng dụng phương pháp học sâu trong phân loại trạng thái kỹ thuật của tấm wafer bán dẫn từ bản đồ kiểm thử
**Deep Learning for Technical State Classification of Semiconductor Wafer Maps**

## Dataset

- Dataset: WM-811K
- Task: 9-class wafer map classification
- Input: wafer map resized to 26x26x3
- Classes: Center, Donut, Edge-Loc, Edge-Ring, Loc, Random, Scratch, Near-Full, None

## Repository Structure

```text
notebooks/   Kaggle notebooks for experiments
src/         Reusable Python code
outputs/     Figures and tables for thesis report

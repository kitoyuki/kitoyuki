# 绘图显示中文
import matplotlib.pyplot as plt
import networkx as nx
from matplotlib import rcParams

rcParams['font.family'] = 'sans-serif'
rcParams['font.sans-serif'] = ['Microsoft YaHei']  # 或其他支持的中文字体
rcParams['axes.unicode_minus'] = False  # 正确显示负号

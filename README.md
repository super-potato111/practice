# 坦克大战（2D，Python + Pygame）

## 项目简介
本项目基于 Python 的 Pygame 库实现经典2D坦克大战游戏。实现玩家坦克移动、射击、敌人坦克自动追踪与射击、场景障碍物、得分统计等功能。

## 功能
- 玩家坦克移动与射击
- 敌人坦克（带简单AI）
- 子弹碰撞检测
- 障碍物与地图
- 得分/生命统计

## 目录结构
```
practice/
├── main.py      # 游戏主循环
├── tank.py      # 玩家坦克类
├── enemy.py     # 敌人坦克类
├── bullet.py    # 子弹类
├── map.py       # 地图与障碍物
├── utils.py     # 工具函数
├── assets/      # 资源文件
│   ├── images/
│   └── sounds/
├── README.md    # 项目文档
```

## 运行方式
1. 安装依赖：
   ```
   pip install pygame
   ```
2. 启动游戏：
   ```
   python main.py
   ```

## 玩法
方向键控制坦克移动，空格键开火。

---
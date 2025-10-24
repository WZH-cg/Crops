pip install tensorflow
pip install torch torchvision torchaudio -i https://pypi.tuna.tsinghua.edu.cn/simple/
pip install opencv-python
pip install numpy
pip install pillow
pip install django==4.2.0

清理缓存并升级工具...
pip cache purge
python -m pip install --upgrade pip setuptools wheel

进入项目目录...
cd .\nongzuowu_bingchonghai\
cd .\crop_pest_detection\

启动开发服务器...
python manage.py runserver

项目根目录/
├── nongzuowu_bingchonghai/
│   └── crop_pest_detection/
│       ├── manage.py
│       ├── requirements.txt
│       └── ... (其他Django项目文件)
└── setup.bat (可选的一键安装脚本)

# chart
本项目可在linux上运行; 本项目包括客户端与服务端;
其中, 客户端包含文件graph_client.py, lang.py, lang_name_code.txt, swp.gif, swsm.gif, ting.gif, translate.py, weather.py;
服务端包含文件 server_main.py, server_mysql.py.

服务端与客户端在终端运行时, 须加上相同的IP与端口, 如:
服务端: ~$python3 server_main.py 0.0.0.0 8000
客户端: ~$python3 grapy_client.py 0.0.0.0 8000

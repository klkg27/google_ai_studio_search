require python >= 3.9
在终端运行以下代码安装google-generativeai
~~~bash
pip install -U google-generativeai
~~~
检查版本号是否为0.8.3
~~~python
import google.generativeai as genai
genai.__version__
~~~
以上方法已弃用，目前需要以下包
~~~
pip install google-genai
pip install openai
~~~

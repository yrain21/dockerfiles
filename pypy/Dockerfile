FROM pypy:2

WORKDIR /code

COPY . /code

RUN pypy -m pip install --no-cache-dir --upgrade pip

RUN pypy -m pip install -r requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple --default-timeout=1000
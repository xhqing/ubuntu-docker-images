FROM xhq123/ubuntu-conda

WORKDIR /app/workdir

RUN pip install pipenv
RUN git clone https://github.com/xhqing/pipenv_patches.git ~/pipenv_patches

CMD ["/bin/zsh"]

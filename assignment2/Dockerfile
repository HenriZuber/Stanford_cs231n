FROM pytorch/pytorch
RUN pip install jupyter matplotlib numpy scipy pillow future Cython 


ENV NVIDIA_VISIBLE_DEVICES all
ENV NVIDIA_DRIVER_CAPABILITIES compute,utility

WORKDIR /opt/assignment2
CMD jupyter notebook --no-browser --ip 0.0.0.0 --allow-root

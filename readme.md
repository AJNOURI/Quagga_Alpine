
Alpine-based Quagga router.
From Docker CLI:
> docker run -ti --name router ajnouri/quagga sh start-quagga.sh

From GNS3 (v1.5), create a new container from image **ajnouri/quagga_alpine** and set as start option **sh start-quagga.sh**


# $FreeBSD$
# All the dts files for rockchip systems we support.

.if ${MACHINE_ARCH} == "armv7"
DTS=	\
	rk3288-firefly-aioc.dts		\
	rk3288-firefly-aioc-lvds.dts	\
	rk3288-firefly-aioc-vga.dts
.elif ${MACHINE_ARCH} == "aarch64"
DTS=	\
	rockchip/rk3399-khadas-edge-captain.dts \
	rockchip/rk3399-khadas-edge.dts \
	rockchip/rk3399-khadas-edge-v.dts \
	rockchip/rk3328-rock64.dts \
	rockchip/rk3399-firefly.dts \
	rockchip/rk3399-rockpro64.dts

DTSO=	rk3328-dwc3.dtso
.endif

.include <bsd.dtb.mk>

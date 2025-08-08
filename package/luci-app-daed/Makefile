include $(TOPDIR)/rules.mk

PKG_NAME:=luci-app-daed
PKG_VERSION:=1.3
PKG_RELEASE:=1
PKG_MIRROR_HASH:=6ee3f5a23b307504e18028406b1f6bfc70835b6a1655a4bf9fe3bef39062545a

LUCI_TITLE:=LuCI Support for DAED
LUCI_DEPENDS:=+daed +curl +libcron +zoneinfo-asia +luci-compat
LUCI_PKGARCH:=all

define Package/$(PKG_NAME)/conffiles
endef

include $(TOPDIR)/feeds/luci/luci.mk
# call BuildPackage - OpenWrt buildroot signature

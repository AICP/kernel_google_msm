mdss-mdp-objs := mdss_mdp.o mdss_mdp_ctl.o mdss_mdp_pipe.o mdss_mdp_util.o
mdss-mdp-objs += mdss_mdp_pp.o
mdss-mdp-objs += mdss_mdp_intf_video.o
mdss-mdp-objs += mdss_mdp_intf_writeback.o
mdss-mdp-objs += mdss_mdp_rotator.o
mdss-mdp-objs += mdss_mdp_overlay.o
mdss-mdp-objs += mdss_mdp_wb.o
obj-$(CONFIG_FB_MSM_MDSS) += mdss-mdp.o
obj-$(CONFIG_FB_MSM_MDSS) += mdss_fb.o

mdss-dsi-objs := mdss_dsi.o mdss_dsi_host.o
mdss-dsi-objs += mdss_dsi_panel.o
mdss-dsi-objs += msm_mdss_io_8974.o
obj-$(CONFIG_FB_MSM_MDSS) += mdss-dsi.o

obj-$(CONFIG_FB_MSM_MDSS_WRITEBACK) += mdss_wb.o

mdss-qpic-objs := mdss_qpic.o mdss_fb.o mdss_qpic_panel.o
obj-$(CONFIG_FB_MSM_QPIC) += mdss-qpic.o
obj-$(CONFIG_FB_MSM_QPIC_ILI_QVGA_PANEL) += qpic_panel_ili_qvga.o

obj-$(CONFIG_FB_MSM_MDSS) += mdss_fb.o

obj-$(CONFIG_FB_MSM_MDSS_DSI_CTRL_STATUS) += mdss_dsi_status.o
obj-$(CONFIG_FB_MSM_MDSS_TIMEOUT_DUMP) += mdss_timeout.o
obj-$(CONFIG_MMI_PANEL_NOTIFICATIONS) += mmi_panel_notifier.o

obj-$(CONFIG_MDSS_QUICKDRAW) += mdss_quickdraw.o

obj-$(CONFIG_FB_MSM_MDSS_KCAL_CTRL) += mdss_mdp_kcal_ctrl.o

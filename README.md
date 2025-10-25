# Filename-including-extension
# ============================================
# 🌍 Shadowrocket / Surge 广告拦截规则（含注释说明）
# 更新：2025-10
# 说明：覆盖国内 + 国际常见广告、统计、追踪、推送域名
# ============================================

# ----------- 📊 中国统计与分析平台 -----------
DOMAIN-SUFFIX,umeng.com,REJECT
DOMAIN-SUFFIX,umeng.co,REJECT
DOMAIN-SUFFIX,umtrack.com,REJECT
DOMAIN-SUFFIX,mta.qq.com,REJECT
DOMAIN-SUFFIX,tajs.qq.com,REJECT
DOMAIN-SUFFIX,log.163.com,REJECT
DOMAIN-SUFFIX,api.talkingdata.com,REJECT
DOMAIN-SUFFIX,talkingdata.net,REJECT
DOMAIN-SUFFIX,sa.uc.cn,REJECT
DOMAIN-SUFFIX,sa.sankuai.com,REJECT
DOMAIN-SUFFIX,log.snssdk.com,REJECT
DOMAIN-SUFFIX,openinstall.io,REJECT
DOMAIN-SUFFIX,openinstall.cn,REJECT
DOMAIN-SUFFIX,hm.baidu.com,REJECT
DOMAIN-SUFFIX,wa.gtimg.com,REJECT
DOMAIN-SUFFIX,gdt.qq.com,REJECT
DOMAIN-SUFFIX,bdtj.tagtic.cn,REJECT
DOMAIN-SUFFIX,bdstatic.com,REJECT

# ----------- 📺 中国广告联盟与视频广告 -----------
DOMAIN-SUFFIX,pangle.cn,REJECT
DOMAIN-SUFFIX,pangolin-sdk-toutiao.com,REJECT
DOMAIN-SUFFIX,ad.toutiao.com,REJECT
DOMAIN-SUFFIX,ad.xiaomi.com,REJECT
DOMAIN-SUFFIX,miui.com,REJECT
DOMAIN-SUFFIX,admob.xiaomi.com,REJECT
DOMAIN-SUFFIX,adview.cn,REJECT
DOMAIN-SUFFIX,adwo.net,REJECT
DOMAIN-SUFFIX,inmobi.cn,REJECT
DOMAIN-SUFFIX,adnet.qq.com,REJECT
DOMAIN-SUFFIX,e.qq.com,REJECT
DOMAIN-SUFFIX,ad.qun.qq.com,REJECT
DOMAIN-SUFFIX,pos.baidu.com,REJECT
DOMAIN-SUFFIX,cpro.baidu.com,REJECT
DOMAIN-SUFFIX,baidustatic.com,REJECT
DOMAIN-SUFFIX,union.youdao.com,REJECT
DOMAIN-SUFFIX,iad.g.163.com,REJECT
DOMAIN-SUFFIX,api.game.163.com,REJECT
DOMAIN-SUFFIX,ad.10086.cn,REJECT
DOMAIN-SUFFIX,ad.cmvideo.cn,REJECT

# ----------- 📱 推送与通知平台 -----------
DOMAIN-SUFFIX,jpush.cn,REJECT
DOMAIN-SUFFIX,getui.com,REJECT
DOMAIN-SUFFIX,igexin.com,REJECT
DOMAIN-SUFFIX,api.jiguang.cn,REJECT
DOMAIN-SUFFIX,xmpush.xiaomi.com,REJECT
DOMAIN-SUFFIX,api-push.meizu.com,REJECT
DOMAIN-SUFFIX,push.hicloud.com,REJECT
DOMAIN-SUFFIX,pushapi.oppo.com,REJECT
DOMAIN-SUFFIX,firebaselogging.googleapis.com,REJECT
DOMAIN-SUFFIX,onesignal.com,REJECT

# ----------- 🌐 国际广告与分析平台 -----------
DOMAIN-SUFFIX,googleadservices.com,REJECT
DOMAIN-SUFFIX,doubleclick.net,REJECT
DOMAIN-SUFFIX,googlesyndication.com,REJECT
DOMAIN-SUFFIX,googletagmanager.com,REJECT
DOMAIN-SUFFIX,googletagservices.com,REJECT
DOMAIN-SUFFIX,ads.google.com,REJECT
DOMAIN-SUFFIX,ads.yahoo.com,REJECT
DOMAIN-SUFFIX,ads.twitter.com,REJECT
DOMAIN-SUFFIX,ads.facebook.com,REJECT
DOMAIN-SUFFIX,connect.facebook.net,REJECT
DOMAIN-SUFFIX,graph.facebook.com,REJECT
DOMAIN-SUFFIX,analytics.tiktok.com,REJECT
DOMAIN-SUFFIX,business-api.tiktok.com,REJECT
DOMAIN-SUFFIX,ads.tiktok.com,REJECT
DOMAIN-SUFFIX,ads.reddit.com,REJECT
DOMAIN-SUFFIX,adservice.google.com,REJECT
DOMAIN-SUFFIX,ads.snapchat.com,REJECT
DOMAIN-SUFFIX,ads.pinterest.com,REJECT
DOMAIN-SUFFIX,adroll.com,REJECT
DOMAIN-SUFFIX,appsflyer.com,REJECT
DOMAIN-SUFFIX,adjust.com,REJECT
DOMAIN-SUFFIX,branch.io,REJECT
DOMAIN-SUFFIX,kochava.com,REJECT
DOMAIN-SUFFIX,criteo.com,REJECT
DOMAIN-SUFFIX,scorecardresearch.com,REJECT
DOMAIN-SUFFIX,quantserve.com,REJECT

# ----------- 🧩 SDK/嵌入式追踪服务 -----------
DOMAIN-SUFFIX,mob.com,REJECT
DOMAIN-SUFFIX,mob.cn,REJECT
DOMAIN-SUFFIX,growingio.com,REJECT
DOMAIN-SUFFIX,sensorsdata.cn,REJECT
DOMAIN-SUFFIX,sentry.io,REJECT
DOMAIN-SUFFIX,bugly.qq.com,REJECT
DOMAIN-SUFFIX,track.tenjin.io,REJECT
DOMAIN-SUFFIX,events.reddit.com,REJECT
DOMAIN-SUFFIX,tracking-protection.cdn.mozilla.net,REJECT
DOMAIN-SUFFIX,adservice.samsungads.com,REJECT
DOMAIN-SUFFIX,ads.nexage.com,REJECT
DOMAIN-SUFFIX,applovin.com,REJECT
DOMAIN-SUFFIX,vungle.com,REJECT
DOMAIN-SUFFIX,ironsrc.com,REJECT
DOMAIN-SUFFIX,unityads.unity3d.com,REJECT

# ----------- 🧱 其他广告与推荐内容 -----------
DOMAIN-SUFFIX,adservice.samsung.com,REJECT
DOMAIN-SUFFIX,adcolony.com,REJECT
DOMAIN-SUFFIX,tapjoy.com,REJECT
DOMAIN-SUFFIX,chartboost.com,REJECT
DOMAIN-SUFFIX,moatads.com,REJECT
DOMAIN-SUFFIX,taboola.com,REJECT
DOMAIN-SUFFIX,outbrain.com,REJECT
DOMAIN-SUFFIX,zedo.com,REJECT
DOMAIN-SUFFIX,revsci.net,REJECT

# ============================================
# ✅ 提示：
# - 导入 Shadowrocket：Rules -> Remote -> 添加此文件 URL（Raw 链接）。
# - 注意部分追踪域名屏蔽后可能导致登录或推送功能异常。
# - 建议逐步测试并手动调整。
# ============================================
# cySentry
使用前端埋点日志sentry，单例模式创建对象
直接初始化let sentry = Report.getInstance(Vue, {})
sentry.log(data = null, type = 'error', options = {})

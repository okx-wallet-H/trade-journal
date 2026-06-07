# 海豚社区 AI 交易主日志
- 启动时间: 2026-06-07T14:21:15+08:00
- 模式: 模拟盘
- 策略: DeepSeek AI 决策 + 趋势跟随

## 运行记录
🔹 模拟盘模式，不会扣真实资金
AI 自动交易机器人启动，每60秒决策一次...
Traceback (most recent call last):
  File "/root/crypto-bot/auto_trade.py", line 109, in <module>
    main()
  File "/root/crypto-bot/auto_trade.py", line 90, in main
    price = get_btc_price()
  File "/root/crypto-bot/auto_trade.py", line 35, in get_btc_price
    market = MarketData.MarketAPI(api_key=DEMO_KEY, secret_key=DEMO_SECRET, passphrase=DEMO_PASSPHRASE, flag=flag)
TypeError: MarketAPI.__init__() got an unexpected keyword argument 'secret_key'
🔹 模拟盘模式 | BTC-USDT 永续合约 | 全仓 | 3x
⚠️ 杠杆设置: Request header OK-ACCESS-PASSPHRASE incorrect. (可能已设置)
AI 合约交易机器人启动，每60秒决策一次...
[14:38:32] BTC: 62064.6 | AI: wait
🤚 观望，无持仓
🔹 模拟盘模式 | BTC-USDT 永续合约 | 全仓 | 3x
⚠️ 杠杆设置: APIKey does not match current environment. (可能已设置)
AI 合约交易机器人启动，每60秒决策一次...
[14:39:30] BTC: 62098.7 | AI: wait
🤚 观望，无持仓

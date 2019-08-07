1.提示
 hql 不能拼接 不能使用in 导致内存增加

riddle_user_info
    check_in // 用作签到
    指定视频_ad
    unlock_cloud // 解锁时间
    
riddle_property
    showMessClick
    showMessClickSuccess
    showMessOpen
    showMessOpenSuccess
    showMessCheckIn
    showMessCheckInSuccess
    lotteryCount   // 记录抽奖数 
    
    
// 队列参数
    
    成语玩家基础属性
        qNum 关卡数
        energy 体力/能量
        videoAdCount 看视频广告的数量
        webAdCount   看插屏广告的数量
    
    记录获取门客

    //  更新用户数据用
    format=Q_M_GAME_USER&virtualHost=DataCenter
    {
        func:"update",
        gameId:110,      // 游戏ID
        playerId:110,    // 玩家ID
        key:"qNum",
        value:100
    }
    
    
   
    
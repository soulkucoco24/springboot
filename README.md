# 雷霆战机-战机训练营协议号


-------------------------------------------------
 协议用途:
 协议号：
 协议参数:
 返回参数:
------------------------------------------------
协议用途：成为教官申请
协议号：349
协议参数：无
返回参数：boolean success(是否成功)
-------------------------------------------------
协议用途：教官收徒请求
协议号： 350
协议参数：long uid(学员的uid)，byte platformTypevalue（平台类型值） 
返回参数: 无
-------------------------------------------------
协议用途：拜师请求
协议号：351
协议参数：long uid(教官的uid) byte platformTypevalue（平台类型值） 
返回参数: 无
-------------------------------------------------
协议用途：学员主动离开教官请求
协议号：352
协议参数：无 
返回参数:无
-------------------------------------------------
协议用途：教官踢人
协议号：353
协议参数：long uid(学员uid) byte platformType （学员平台类型值） 
返回参数:
-------------------------------------------------
协议用途：教官推荐
协议号：354
协议参数：int index (defaut value is zero) 
返回参数:List<BaseInfoPo> int index (defaut value is zero)
-------------------------------------------------
协议用途：学员推荐
协议号：355
协议参数：int index (defaut value is zero) 
返回参数: List<BaseInfoPo> int allNum;
-------------------------------------------------
协议用途：教官训练营消息处理
协议号：356
协议参数：int 操作类型（枚举） long message（消息id) long muid(目标用户uid) byte mplatfromType（目标用户平台值）
返回参数:待定
-------------------------------------------------
 协议用途：任务变更 进入的时候回给定默认值,
 协议号：357
 协议参数： int chengeNum（改变次数）long uid(学员uid) byte PlatfromType(学员平台值)
 返回参数:  int taskNum（任务数量） List<Short> taskList（任务id集合）short masterTaskId (师傅奖励id)  int chengeNum变更次数
-------------------------------------------------
协议用途：任务列表
协议号：358
协议参数：无
返回参数:List<View> View:baseInfor,List<ids> changeNum,mastertaskId,isSave,
-------------------------------------------------
协议用途：学员列表
协议号：359
协议参数：无
返回参数:int num  List<BaseInfoPo>
-------------------------------------------------
协议用途：查找教官或学员
协议号：360
协议参数：long uid 
返回参数:int num  List<BaseInfoPo>
-------------------------------------------------
协议用途:教官训练营入口协议
协议号：361
协议参数：无
返回参数:short 英雄模式进度
 -------------------------------------------------
 协议用途：教官保存任务
 协议号：362
 协议参数： long auid;PlatformType aplatformType;
 返回参数: int taskNum;List<Short> taskList;short masterTaskId;int chengeNum;
 --------------------------------------------
 协议用途：获取学员任务列表
 协议号：363
 协议参数：待定
 返回参数:   Map<Short, String> dayTaskMap;//日常奖励
 short weekTakNum;//周次数
 Short weekTaskId;//周奖励id
 String weekTaskProgress;//周奖励类型
 Short twiceNum;//固定奖励次数
 List<Short> twiceIdList;//固定奖励类型
  --------------------------------------------

 

语料库样本（200 句）

本文件是老年群体推销话语语料库的验收样本。从全量 4,997 句中抽取 200 句，直播 130 句（A 路 70、B 路 60）、短视频 70 句，字段与判定口径与全量一致。

一、字段

  id        句号，L0001 起为直播，V0001 起为短视频
  channel   A、B 为直播的两路信号，V 为短视频
  subcorpus live 或 shortvideo
  text      句子文本
  searle    言语行为
  p4g       说服策略

二、标注体系

第一层为言语行为，采用 Searle（1979）五分法，另设「其他」兜底，该层穷尽：
  assertive / directive / commissive / expressive / declaration / other

第二层为说服策略，采用 Wang 等（2019）十一类：
  logical / emotion / credibility / foot_in_door / self_modeling / personal_story /
  donation_info / source_inquiry / task_inquiry / personal_inquiry / non_strategy

判定顺序为先言语行为、后说服策略；一句多行为取句末主导；两层均为单标签。

三、本样本构成

  总句数：200，直播 130、短视频 70

  言语行为：assertive 131、directive 54、commissive 8、expressive 4、
            declaration 2、other 1

  说服策略：non_strategy 110、logical 47、emotion 20、credibility 18、
            personal_story 3、foot_in_door 1、self_modeling 1

四、一致性

  两人独立双盲标注 500 句，按 A 路、B 路、短视频三层分层抽取。
  言语行为 κ=0.74、观测一致率 85%；说服策略 κ=0.66、观测一致率 79%。
  十一类中「购买信息」与「来源探询」在语料中无实例。

五、全量语料

  全量 4,997 句、162,395 字（含标点），字段与标注体系与本样本完全一致。

语料库样本（200 句）

为了便于传输和验收，从全部语料中抽取两个批次共 200 句（直播 100 句、短视频 100 句），
每句均完成两层标注。结构与标注口径与全量语料完全一致。

一、标注体系

第一层为言语行为，采用 Searle（1979）五分法，另设「其他」兜底，该层穷尽：
  assertive / directive / commissive / expressive / declaration / other

第二层为说服策略，采用 Wang 等（2019）十一类：
  logical / emotion / credibility / foot_in_door / self_modeling / personal_story /
  donation_info / source_inquiry / task_inquiry / personal_inquiry / non_strategy

判定顺序为先言语行为、后说服策略；一句多行为取句末主导；两层均为单标签。

二、字段

  seg_id / subcorpus / text / searle / p4g / note

三、本样本构成

  总句数：200（直播 100 / 短视频 100）
  言语行为分布：{'assertive': 113, 'directive': 71, 'commissive': 7, 'declaration': 4, 'other': 2, 'expressive': 3}
  说服策略分布：{'non_strategy': 116, 'foot_in_door': 3, 'emotion': 16, 'logical': 46, 'credibility': 13, 'personal_inquiry': 1, 'self_modeling': 3, 'personal_story': 2}

四、全量语料（备注）

  总句数：5,008 句
  子库一：直播带货，26 个分片，246.2 分钟，2,350 句
  子库二：健康类短视频，109 条，286.5 分钟，2,658 句
  文本量：162,915 字
  标注：两层均已完成，无空缺
  一致性：言语行为 κ=1.00，说服策略 κ=0.93
  全量数据见同级「全量语料」文件夹，结构与字段与本样本完全一致。

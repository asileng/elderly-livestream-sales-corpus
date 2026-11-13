语料库样本（200 句）

直播 100 句、短视频 100 句，每句两层标注。与全量语料结构一致。

字段

  id         句号。L0001 为直播，V0001 为短视频
  subcorpus  live 或 shortvideo
  text       句子文本
  searle     言语行为：assertive / directive / commissive / expressive / declaration / other
  p4g        说服策略：logical / emotion / credibility / foot_in_door / self_modeling /
             personal_story / donation_info / source_inquiry / task_inquiry /
             personal_inquiry / non_strategy
  note       判定说明

标注

  先判言语行为，再判说服策略，各取一个主标签。
  一句出现两个行为时取句末那个。

全量

  5,008 句（直播 2,350、短视频 2,658），不在本仓库内，可按研究用途申请。

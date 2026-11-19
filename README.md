# CV2025_review

冠层图与叶面斑块研究相关 GitHub 开源项目集中目录。此处汇总来自两份《开源代码清单》的项目，已按 `owner/repo` 去重。

**统计：** 原始清单共 10 个项目条目，跨清单重复 2 个（`ultralytics/ultralytics`、`zkkli/RepQ-ViT`），合并后 **8 个唯一项目**。原测试项目 `BinayKSingh/CCFF` 已从当前目录移除。

**代码导入结果：** 6 个项目的公开源码已复制到本仓库对应目录；EMCAD 与 PlantSeg 因许可问题仅收录链接。可查看 [GitHub Actions 成功运行记录](https://github.com/FCYCY444/CV2025_review/actions/runs/44545628414)及[导入报告](./import-reports/latest-import.md)。

## 项目目录（按原仓库名命名）

| 本仓库目录 | 原始 GitHub 仓库 | 对应方向 | 许可证 / 复制限制 | 保存状态 |
| --- | --- | --- | --- | --- |
| [ultralytics](./ultralytics/) | [ultralytics/ultralytics](https://github.com/ultralytics/ultralytics) | 冠层图；叶面斑块 | AGPL-3.0 | 已复制源码 |
| [FGD](./FGD/) | [yzd-v/FGD](https://github.com/yzd-v/FGD) | 冠层图 | Apache-2.0 | 已复制源码 |
| [yolov12](./yolov12/) | [sunsmarterjie/yolov12](https://github.com/sunsmarterjie/yolov12) | 冠层图 | AGPL-3.0 | 已复制源码 |
| [RepQ-ViT](./RepQ-ViT/) | [zkkli/RepQ-ViT](https://github.com/zkkli/RepQ-ViT) | 冠层图；叶面斑块 | Apache-2.0 | 已复制源码 |
| [EMCAD](./EMCAD/) | [SLDGroup/EMCAD](https://github.com/SLDGroup/EMCAD) | 叶面斑块 | UT Austin Research License（限制再分发） | 仅保存链接 |
| [PlantSeg](./PlantSeg/) | [tqwei05/PlantSeg](https://github.com/tqwei05/PlantSeg) | 叶面斑块 | 仓库级许可未核实 | 仅保存链接 |
| [sam2](./sam2/) | [facebookresearch/sam2](https://github.com/facebookresearch/sam2) | 叶面斑块 | Apache-2.0（另见仓库其他许可文件） | 已复制源码 |
| [DualBranchSSLDomainAdaptation](./DualBranchSSLDomainAdaptation/) | [ARGhanbari/DualBranchSSLDomainAdaptation](https://github.com/ARGhanbari/DualBranchSSLDomainAdaptation) | 叶面斑块 | MIT | 已复制源码 |

## 使用说明

- 每个项目仅建立 **一份** 同名文件夹，跨研究方向重复出现的上游仓库在一处复用。
- 子目录中的 `SOURCE.md` 记录上游原始链接、对应方法、优先阅读的文件及许可信息。
- **来源索引与代码副本是两回事。** 目录里只有 `SOURCE.md` 时，代表仅保存链接；如果目录中另有原始源码文件，则属于已镜像保存的文件。
- `EMCAD` 使用 UT Austin Research License，`PlantSeg` 未核实仓库级许可，因此仅保存链接，不在本公开仓库重新发布其源码。
- `ultralytics`、`yolov12` 适用 AGPL-3.0，复制或改动时需要遵守对应的开源条件；其他项目也应逐一遵守原始许可证。
- 来源清单中提及的 Bi-AFPN-P2 与 TDA-YOLO 作者实现尚未核实，没有可确定的原仓库链接，因此本次没有作为额外项目收录。

机器可读条目见 [projects.csv](./projects.csv)。

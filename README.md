# birdclef ~6/1

LeaderBoard 399th /828teams
Private Score 0.56
Public Score 0.62

## my best model
Voting 3vote
| model | batch size | ep | fold | Aug |
| ----- | ---------- | -- | ---- |----- |
| resnest50d_4s2x40d | 10 | 15 | 0 | specAug |
| eca_nfnet_l0 | 10 | 15 | 0 | specAug |
| tf_efficientnet_b5_ns | 12 | 13 | 1 | specAug |
| tf_efficientnet_b4 | 20 | 12 | 0 | specAug |
| swsl_resnet50 | 30 | 15 | 0 | specAug |
| resnext50_32x4d | 50 | 12 | 3 | specAug |
| tf_efficientnet_b0_ns | 20 | 12 | 4 | specAug |
| densenet121 | 20 | 12 | 3 | specAug |
| densenet201 | 20 | 15 | 2 | specAug |
| resnest50d | 100 | 12 | 0 | specAug |

## What I tried.
### Loss
- BCEWithLogitsLoss
- bi_tempered_logistic_loss
- BCEFocalLoss

### Augment
- SpecAugment
- GaussianNoise
- PinkNoise
- PitchShift
- TimeShift

### models
- efficientnetv2_rw_m
- eca_nfnet_l1
- swin_small_patch4_window7_224

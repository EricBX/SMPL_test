# SMPL_test
To test SMPL models.

Initial codes are borrowed from [CalciferZh/SMPL](https://github.com/CalciferZh/SMPL) and [vchoutas/smplx](https://github.com/vchoutas/smplx).

## TODOs
- [x] SMPL in Numpy (1.19.1)
- [x] SMPL in PyTorch (1.5.0, 1.6.0)
- [x] SMPL in TensorFlow (1.13.1)
- [ ] SMPL Animation
- [x] SMPL-X in PyTorch (1.6.0) (pre-build smplx needed)
- [ ] SMPL-X Animation

## Directory Tree
.\
├── LICENSE\
├── model_female.pkl\
├── model_male.pkl\
├── model_neutral.pkl\
├── model.pkl\
├── models\
│   ├── basicModel_f_lbs_10_207_0_v1.0.0.pkl\
│   ├── basicModel_m_lbs_10_207_0_v1.0.0.pkl\
│   ├── smpl\
│   │   ├── SMPL_FEMALE.pkl\
│   │   ├── SMPL_MALE.pkl\
│   │   └── SMPL_NEUTRAL.pkl\
│   ├── smplh\
│   │   ├── SMPLH_FEMALE.pkl\
│   │   └── SMPLH_MALE.pkl\
│   └── smplx\
│       ├── SMPLX_FEMALE.npz\
│       ├── SMPLX_FEMALE.pkl\
│       ├── SMPLX_MALE.npz\
│       ├── SMPLX_MALE.pkl\
│       ├── SMPLX_NEUTRAL.npz\
│       └── SMPLX_NEUTRAL.pkl\
├── preprocess.py\
├── README.md\
├── smpl_np.py\
├── smpl_tf.py\
├── smpl_torch_batch.py\
├── smpl_torch.py\
├── smplx\
│   ├── body_models.py\
│   ├── \_\_init__.py\
│   ├── joint_names.py\
│   ├── lbs.py\
│   ├── utils.py\
│   ├── vertex_ids.py\
│   └── vertex_joint_selector.py\
├── smplx_demo.py\
├── test.py\
├── tools\
│   ├── clean_ch.py\
│   ├── \_\_init__.py\
│   ├── merge_smplh_mano.py\
│   └── README.md

Please prepare model files before running the code. 
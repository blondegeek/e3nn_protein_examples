* `create_helix_dataset.ipynb` : Notebook for generating helix dataset. You can change the level of noise and various parameterizations of the geometry.
* `helix_predict_displacements_and_frames.ipynb` : predict displacements and coordiante frames given initial structure and frames.
* `generate_from_backbone.ipynb`: predict the vertices of tetrahedra from their centers as a projection onto spherical harmonics centered on centers.

`datasets/`
  * `data.torch` : pre-computed dataset for `helix_predict_displacements_and_frames.ipynb`
  * `4_tetra_50_frames.npz` : pre-computed dataset for `generate_from_backbone.ipynb`. vertices and centers of 4 edge-sharing tetrahedra.

`models/`
  * `helix_model_3_layer.npz`: torch model parameters for `helix_predict_displacements_and_frames.ipynb` to start exploring the notebook.
  * `tetra_model_4_layer.npz`: torch model parameters for `generate_from_backbone.ipynb` to start exploring the notebook.



python matconvnet_hr101_to_pickle.py --matlab_model_path hr_res101.mat --weight_file_path  networks/mat2tf.pkl
      
    python tiny_face_eval.py --weight_file_path networks/mat2tf.pkl --data_dir images/input --output_dir images/output
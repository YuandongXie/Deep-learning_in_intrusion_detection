# Deep-learning_in_intrusion_detection
1.The experiment requires KDD_99 datasets,NSL_KDD datasets and CIC_IDS_2017/2018 datasets,please download them in the main directory with path name as follows:main directory/KDD_99(NSL_KDD/CIC_IDS_2017/CIC_IDS_2018)
2.To run this experiment,you should run prepare_data.py after you download all the datasets mentioned above.Then execute run_experiments in powershell or cmd in the main directory with command as follows:
python run_experiments.py experiment_specs\selected_model_tests\selected_ae_ann.csv.You can change the selected models as your wish,but please name them correctly.
3.The main frame comes from this paper:Sunanda Gamage et al.Deep learning methods in network intrusion detection:A survey and an objective comparison,yet they used an ancient version of tensorflow(1.12.0),which is evenly not able in most mirror sites,which lead to a set of problems.
4.The pickle module used to save trained models also didn't perform well on windows,nonetheless,it can still get loss function value normaly,so it's acceptable

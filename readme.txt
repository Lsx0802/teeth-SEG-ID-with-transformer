To install dependencies:

conda create --name <your_env_name> --file requirements.txt
##need monai

To run the training code with default parameters (check parser.py for data paths):
python ICT/train.py
pretrain weight：cbctseg_model_state_dict.pt
1. Download all the datasets from the project report references. 

2. Ensure you have the directories set up in the same folder as the notebooks, if needed rename the folders of the directories to follow this format:
dataset downloads correspond to the links for each directory

all_real_dir = 'real_people' https://www.kaggle.com/datasets/arnaud58/flickrfaceshq-dataset-ffhq
celeb_real = 'celeba/img_align_celeba/img_align_celeba' https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html
more_real_train = 'real_fake/real_vs_fake/real-vs-fake/train/real' https://www.kaggle.com/datasets/xhlulu/140k-real-and-fake-faces
more_real_test = 'real_fake/real_vs_fake/real-vs-fake/test/real' https://www.kaggle.com/datasets/xhlulu/140k-real-and-fake-faces
more_real_valid = 'real_fake/real_vs_fake/real-vs-fake/valid/real' https://www.kaggle.com/datasets/xhlulu/140k-real-and-fake-faces
more_fake_train = 'real_fake/real_vs_fake/real-vs-fake/train/fake' https://www.kaggle.com/datasets/xhlulu/140k-real-and-fake-faces
more_fake_test = 'real_fake/real_vs_fake/real-vs-fake/test/fake' https://www.kaggle.com/datasets/xhlulu/140k-real-and-fake-faces
more_fake_valid = 'real_fake/real_vs_fake/real-vs-fake/valid/fake' https://www.kaggle.com/datasets/xhlulu/140k-real-and-fake-faces
train_real_dir = 'Dataset/Train/Real' https://www.kaggle.com/datasets/manjilkarki/deepfake-and-real-images
train_fake_dir = 'Dataset/Train/Fake' https://www.kaggle.com/datasets/manjilkarki/deepfake-and-real-images
test_real_dir = 'Dataset/Test/Real' https://www.kaggle.com/datasets/manjilkarki/deepfake-and-real-images
validation_real_dir = 'Dataset/Validation/Real' https://www.kaggle.com/datasets/manjilkarki/deepfake-and-real-images
validation_fake_dir = 'Dataset/Validation/Fake' https://www.kaggle.com/datasets/manjilkarki/deepfake-and-real-images
test_fake_male_dir = 'ThisPersonDoesNotExist/male' https://www.kaggle.com/datasets/bwandowando/all-these-people-dont-exist
test_fake_female_dir = 'ThisPersonDoesNotExist/female' https://www.kaggle.com/datasets/bwandowando/all-these-people-dont-exist

3. Ensure you have the model folders both in the same folder as you are running the notebooks. 

4. Only run demo_script.ipynb to see the models work, do not re run the notebooks final_project_with_fake or final_project unless you are trying to retrain the model.

5. final_project_with_fake is trained with the dataset 'ThisPersonDoesNotExist', final_project is not trained with this dataset. Info about each network can be viewed by running the notebooks.

6. Do not run the training cells as you will overwrite the models

7. Use demo_script to have the model predict
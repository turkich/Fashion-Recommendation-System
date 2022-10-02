# Fashion-Recommendation-System
A fashion recommendation system based on images

Module-1:Pose detction file "CS2_Module_1.ipynb"
Module-2:Fashion Object detection and localizaton file "CS2_Module_2.ipynb"
Module-3,4: Embedding Generation and retrival of thoes embeddings(fashion-objects)
file "CS2_Module_3_4.ipynb"
End to End pipeline can be found in file "CS2_final_predict.ipynb"


First step: 

   Crop images obtained by the the garment detection (Sahar's code) 
   with the the notebook "Crop_images_BuyMeThatLook" :
            This notebook take images and a Json file that contain the keypoints from the bounding boxes in order to crop images by item

    => this cropped images are used to test the code (input of the user)

Second step:

    Run the notebook "CS2_Module_3_4" or "Module_3_4_with_pytorch" to:
        -Extract embeddings from the scrapped data
        -Configure Elastic search database
        -Store the embeddings to the database
        -Search similarity
        -get the results

    Ps: you can run Second step with: 
        Tensorflow: CS2_Module_3_4
        Pytorch: Module_3_4_with_pytorch

Third step:

    To Visualize the results run the notebook "Visualisation_of_the_response"

To fine tune the model you can use the notebook: Fine_tuning_model

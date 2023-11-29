# deep-learning-challenge
Overview of the analysis: 
    The purpose of this analysis is to build a deep learning model to predict whether applicants for Alphabet Soup, an organization that provides funding to charitable organizations, will be successful in using the money effectively. The analysis aims to identify the key factors that influence the success of these applications and provide insights to optimize the allocation of funds.
Results: Using bulleted lists and images to support your answers, address the following questions:

    Data Preprocessing

        What variable(s) are the target(s) for your model?
            Target: IS_SUCCESSFUL
        What variable(s) are the features for your model?
            Feature Variables: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT
        
        What variable(s) should be removed from the input data because they are neither targets nor features?
            Variables to Remove: EIN, NAME
    Compiling, Training, and Evaluating the Model

        How many neurons, layers, and activation functions did you select for your neural network model, and why?
            Number of Layers: Two hidden layers and an output layer.
            Number of Neurons: 80 on the first, 50 on the second
            Activation Functions: ReLU for the hidden layers and Sigmoid for the output layer since this is a binary classification problem.
        Were you able to achieve the target model performance?
            The Accuracy is 0.728
    What steps did you take in your attempts to increase model performance?
        I add more epochs and nodes. And I try to use the AutoOptimization to find a better way, but it is taking to long.
Summary:
    In summary, the deep learning model was built to predict the success of funding applications for Alphabet Soup. The recommended architecture includes two hidden layers with ReLU activation functions and a sigmoid output layer. However, achieving the target model performance may require further data preprocessing, feature engineering, hyperparameter tuning, regularization, and potentially exploring more advanced architectures.
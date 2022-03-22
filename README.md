create env

'''bash
conda create -n wineq python==3.7 -y

actitvate env

install req
'''touch 


mlflow server command - 


mlflow server \
    --backend-store-uri sqlite:///mlflow.db \
    --default-artifact-root ./artifacts \
    --host 0.0.0.0 -p 1234
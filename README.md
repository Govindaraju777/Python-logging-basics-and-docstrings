# Python scripting and modular coding of Perceptron


## basic log config

      import logging
      import os

      logging.basicConfig(
          filename=os.path.join(log_dir, "running_logs.log"),
          level=logging.INFO,
          format='[%(asctime)s: %(levelname)s: %(module)s]: %(message)s',
          filemode='a'
          )

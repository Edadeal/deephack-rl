# Train

cd PolicyGradient/a3c
python train.py --env Skiing-v0 --model_dir model

# Eval

cd PolicyGradient/a3c
python eval.py --env Skiing-v0 --model_dir model

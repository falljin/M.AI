!pip install numpy scipy matplotlib torchaudio librosa soundfile
# load data
data = torchaudio.datasets.LIBRISPEECH("./", url="test-clean", download=True)
sample = data[0]
s1 = sample[0]
s1 = s1.numpy()
sr1 = sample[1]

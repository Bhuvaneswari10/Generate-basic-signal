# Generate-basic-signal
values = -1:0.1:1;
singleCycleWave = ones(100,1) * values;
singleCycleWave = reshape(singleCycleWave,numel(singleCycleWave),1);

plot(singleCycleWave)
xlabel('Index')
ylabel('Amplitude')

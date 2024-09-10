### Intro
- Both first two paragraphs start with "In this notebook"

- import sciebo before downloading dataset, but sciebo is not installed earlier
    - And do all participants have access to sciebo?

- IMPORTANT: I had to pip install pysciebo, netCDF4, and h5netcdf to be able to load the data

### Spike Timing Data as Pandas DataFrame

"**Which** cells spiked in each trial. **Hint** - use `df.groupby('spike_trial')`"
    - Based on the solution it should be "How many .."

"Find the trial number and the spike count where the least number of cells spiked"
- "Fewest cells spiked"

Isn't there something off about the response time to spikes in raster plots analysis? Aren't the sorted trials column the wrong trial numbers for the spikes in the spike_time column when the spikes are sorted by response time?
    - Have to think about this.



**Note that the packages that are needed should all be added to the pip install line in the first cell. Seaborn was missing here. This applies to all notebooks.**

Collaborators: Ashton Southwick

Good and bad plots:
Good:

<img width="990" height="525" alt="Screenshot 2025-11-10 154018" src="https://github.com/user-attachments/assets/ae278084-ec27-446d-921d-3520ee72df16" />

Shows both a normalized noisy spectrum and a normalized smoothed spectrum from 4000 Angstrom to just over 10000 Angstrom. This figure is quite easy to interpret: the red line is an idealized noise-free spectrum, and the black lines are synthetic noisy spectra.


Bad:

<img width="886" height="357" alt="Screenshot 2025-11-10 155509" src="https://github.com/user-attachments/assets/50db838d-ed7f-4e83-9a73-485837ee6701" />

Shows many overplotted spectra from the same object, essentially a time series of the object's spectrum. The colorbar indicates the MJD, where purple is the earliest observation, and yellow indicates the latest. If it showed a clear time series evolution (e.g. the spectrum getting fainter/brighter as time passed), it would be a better plot.

# ORIGINAL PLOT #

<img width="860" height="858" alt="image" src="https://github.com/user-attachments/assets/6b8c766d-1872-410b-99de-4ac53289d6c1" />


# UPDATED PLOT #

<img width="841" height="825" alt="image" src="https://github.com/user-attachments/assets/5259fbe2-090b-4db5-bff4-b758decd819b" />

The original plot was nearly impossible to read. The figure was overclustered and the axes labels were illegible. I updated it into a heatmap using a diverging colormap (coolwarm). I removed the overlapping axes labels and reduced the cluttering. I used the diverging colormap to highlight negative vs positive correlations. These changes make the heatmap much more readable. Although there is still a lot of data, and there are no axes labels due to the lack of information about the specific genes, it is still a better alternative to the previous plot.

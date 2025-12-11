# SRDT
Synthethic and real data set employed to study the impact of turbidity as an isolated parameter under the values of 0, 0.7, 1.2, 1.5, 2.0 and 2.5 FTU


The file should contain:
links to our synthethic data as well the blender file. 
Different turbidities table (mean. median and standar deviation)
real data and annotated real data
table with more details of the models employed
table with all parameters calculated mPrediction, mAccuracy, mDice, mIoU
Table with the objects (pool aswell) employed as well as their dimension and materials
Kaolin link and sensors
a more detailed explanation of how the apparent absorbance is developed to provide the color absorbance and the scattering coefficients 

[Data set in Zenobo](https://zenodo.org/uploads/17866606)

Results for Mask2Former (Swin-S) at 25K iterations, when the model has been trained in specific turbidity conditions. Verification has been made in the validation subset of synthetic and in the real data set: 

<h2>Synthetic vs Real – Turbidity Training Evaluation </h2>

<table>
  <thead>
    <tr>
      <th rowspan="2">Training turbidity</th>
      <th colspan="3">Synthetic (itself) </th>
      <th colspan="5">T1 (real)</th>
      <th colspan="5">T2 (real)</th>
      <th colspan="5">T3 (real)</th>
      <th colspan="5">T4 (real)</th>
      <th colspan="5">T5 (real)</th>
      <th colspan="5">T6 (real)</th>
      <th colspan="5">T1–6 (real)</th>
    </tr>
    <tr>
      <!-- Synthetic -->
      <th>mIoU</th><th>mAcc</th><th>mDice</th>
      <!-- T1 -->
      <th>mIoU</th><th>mAcc</th><th>mDice</th><th>mRec</th><th>mPrec</th>
      <!-- T2 -->
      <th>mIoU</th><th>mAcc</th><th>mDice</th><th>mRec</th><th>mPrec</th>
      <!-- T3 -->
      <th>mIoU</th><th>mAcc</th><th>mDice</th><th>mRec</th><th>mPrec</th>
      <!-- T4 -->
      <th>mIoU</th><th>mAcc</th><th>mDice</th><th>mRec</th><th>mPrec</th>
      <!-- T5 -->
      <th>mIoU</th><th>mAcc</th><th>mDice</th><th>mRec</th><th>mPrec</th>
      <!-- T6 -->
      <th>mIoU</th><th>mAcc</th><th>mDice</th><th>mRec</th><th>mPrec</th>
      <!-- T1–6 -->
      <th>mIoU</th><th>mAcc</th><th>mDice</th><th>mRec</th><th>mPrec</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>T1</b></td>
      <td>98.7</td><td>99.37</td><td>99.35</td>
      <td>70.81</td><td>83.00</td><td>78.96</td><td>83.0</td><td>84.8</td>
      <td>70.08</td><td>84.97</td><td>79.12</td><td>85.0</td><td>82.3</td>
      <td>58.66</td><td>74.35</td><td>69.86</td><td>74.4</td><td>68.7</td>
      <td>56.58</td><td>71.86</td><td>68.16</td><td>71.9</td><td>69.0</td>
      <td>42.31</td><td>56.88</td><td>55.13</td><td>56.9</td><td>61.3</td>
      <td>33.84</td><td>50.64</td><td>45.62</td><td>50.6</td><td>56.9</td>
      <td>59.75</td><td>74.97</td><td>71.20</td><td>75.0</td><td>71.1</td>
    </tr>
    <tr>
      <td><b>T2</b></td>
      <td>98.5</td><td>99.32</td><td>99.24</td>
      <td>76.46</td><td>86.11</td><td>85.64</td><td>86.1</td><td>87.7</td>
      <td>72.40</td><td>86.60</td><td>82.19</td><td>86.6</td><td>82.0</td>
      <td>58.55</td><td>74.01</td><td>69.84</td><td>74.0</td><td>68.3</td>
      <td>61.14</td><td>74.00</td><td>72.02</td><td>74.0</td><td>72.7</td>
      <td>44.94</td><td>57.27</td><td>57.44</td><td>57.3</td><td>63.0</td>
      <td>37.38</td><td>53.62</td><td>50.53</td><td>53.6</td><td>59.9</td>
      <td>62.81</td><td>76.69</td><td>74.50</td><td>76.7</td><td>74.3</td>
    </tr>
    <tr>
      <td><b>T3</b></td>
      <td>98.08</td><td>99.20</td><td>99.03</td>
      <td>75.89</td><td>86.49</td><td>84.69</td><td>87.6</td><td>86.5</td>
      <td>73.30</td><td>87.23</td><td>82.10</td><td>87.2</td><td>84.0</td>
      <td>62.83</td><td>78.49</td><td>75.53</td><td>78.5</td><td>72.3</td>
      <td>64.93</td><td>79.57</td><td>75.93</td><td>79.6</td><td>75.3</td>
      <td>47.36</td><td>67.64</td><td>60.32</td><td>67.6</td><td>60.4</td>
      <td>42.33</td><td>65.01</td><td>54.09</td><td>65.0</td><td>57.2</td>
      <td>60.53</td><td>78.04</td><td>72.60</td><td>78.0</td><td>72.5</td>
    </tr>
    <tr>
      <td><b>T4</b></td>
      <td>97.36</td><td>98.81</td><td>98.66</td>
      <td>80.10</td><td>88.65</td><td>88.38</td><td>88.6</td><td>89.7</td>
      <td>76.18</td><td>88.39</td><td>85.06</td><td>88.9</td><td>85.1</td>
      <td>59.76</td><td>76.16</td><td>71.62</td><td>76.2</td><td>69.8</td>
      <td>63.19</td><td>77.19</td><td>74.56</td><td>77.2</td><td>73.8</td>
      <td>48.64</td><td>65.83</td><td>61.42</td><td>65.8</td><td>62.6</td>
      <td>39.43</td><td>63.52</td><td>55.92</td><td>63.5</td><td>59.3</td>
      <td>61.41</td><td>77.49</td><td>73.70</td><td>77.5</td><td>72.1</td>
    </tr>
    <tr>
      <td><b>T5</b></td>
      <td>96.18</td><td>98.41</td><td>98.04</td>
      <td>81.57</td><td>89.69</td><td>89.49</td><td>89.7</td><td>90.2</td>
      <td>78.15</td><td>89.95</td><td>87.00</td><td>90.0</td><td>86.7</td>
      <td>65.55</td><td>80.06</td><td>77.17</td><td>80.1</td><td>75.9</td>
      <td>64.00</td><td>79.00</td><td>75.88</td><td>79.0</td><td>75.7</td>
      <td>53.06</td><td>71.08</td><td>66.24</td><td>71.1</td><td>66.3</td>
      <td>46.33</td><td>64.15</td><td>58.66</td><td>64.1</td><td>62.3</td>
      <td>64.15</td><td>79.81</td><td>76.50</td><td>79.8</td><td>75.0</td>
    </tr>
    <tr>
      <td><b>T6</b></td>
      <td>93.16</td><td>96.30</td><td>96.42</td>
      <td>68.32</td><td>82.44</td><td>78.74</td><td>82.4</td><td>79.3</td>
      <td>70.69</td><td>85.58</td><td>81.08</td><td>85.6</td><td>80.8</td>
      <td>54.41</td><td>72.32</td><td>66.55</td><td>72.3</td><td>66.7</td>
      <td>59.76</td><td>74.71</td><td>71.47</td><td>74.7</td><td>72.4</td>
      <td>44.02</td><td>63.03</td><td>57.02</td><td>63.0</td><td>57.4</td>
      <td>36.07</td><td>57.44</td><td>48.31</td><td>57.4</td><td>53.0</td>
      <td>55.02</td><td>73.65</td><td>68.10</td><td>73.6</td><td>67.0</td>
    </tr>
    <tr>
      <td><b>T1–6</b></td>
      <td>97.01</td><td>98.55</td><td>98.00</td>
      <td>78.59</td><td>87.80</td><td>87.05</td><td>87.8</td><td>88.3</td>
      <td>74.90</td><td>88.77</td><td>84.29</td><td>88.8</td><td>83.9</td>
      <td>64.21</td><td>79.84</td><td>75.85</td><td>79.8</td><td>74.9</td>
      <td>64.28</td><td>80.34</td><td>76.21</td><td>80.3</td><td>74.9</td>
      <td>51.34</td><td>70.50</td><td>64.10</td><td>70.5</td><td>61.5</td>
      <td>42.53</td><td>66.81</td><td>55.93</td><td>66.8</td><td>56.1</td>
      <td>66.35</td><td>82.03</td><td>77.80</td><td>82.0</td><td>76.0</td>
    </tr>
    <tr>
  <td><b>T1,2,3</b></td>
  <td>98.22</td><td>99.25</td><td>99.10</td>
  <td>73.14</td><td>85.27</td><td>82.30</td><td>85.3</td><td>84.6</td>
  <td>69.26</td><td>85.83</td><td>78.60</td><td>85.8</td><td>79.2</td>
  <td>56.94</td><td>75.46</td><td>68.20</td><td>75.5</td><td>66.3</td>
  <td>58.82</td><td>75.29</td><td>70.28</td><td>75.3</td><td>69.5</td>
  <td>48.48</td><td>64.28</td><td>60.82</td><td>64.3</td><td>62.0</td>
  <td>39.87</td><td>59.07</td><td>51.70</td><td>59.1</td><td>56.4</td>
  <td>57.46</td><td>75.23</td><td>69.42</td><td>75.2</td><td>67.9</td>
</tr>

<tr>
  <td><b>T2,3,4</b></td>
  <td>97.98</td><td>99.10</td><td>98.98</td>
  <td>81.23</td><td>88.95</td><td>89.13</td><td>88.9</td><td>90.7</td>
  <td>77.22</td><td>89.16</td><td>86.09</td><td>89.2</td><td>86.4</td>
  <td>66.29</td><td>80.05</td><td>77.33</td><td>80.1</td><td>76.7</td>
  <td>67.64</td><td>80.86</td><td>78.43</td><td>80.9</td><td>77.7</td>
  <td>53.28</td><td>70.57</td><td>70.01</td><td>70.6</td><td>65.4</td>
  <td>44.56</td><td>66.90</td><td>57.09</td><td>66.9</td><td>59.1</td>
  <td>64.37</td><td>79.90</td><td>76.48</td><td>79.9</td><td>75.3</td>
</tr>

<tr>
  <td><b>T3,4,5</b></td>
  <td>97.43</td><td>98.71</td><td>98.69</td>
  <td>81.50</td><td>88.91</td><td>89.43</td><td>88.9</td><td>90.8</td>
  <td>75.67</td><td>88.36</td><td>85.16</td><td>-</td><td>-</td>
  <td>65.03</td><td>79.15</td><td>76.49</td><td>-</td><td>-</td>
  <td>68.39</td><td>80.58</td><td>79.39</td><td>-</td><td>-</td>
  <td>49.70</td><td>68.77</td><td>63.32</td><td>-</td><td>-</td>
  <td>43.44</td><td>66.21</td><td>56.73</td><td>-</td><td>-</td>
  <td>63.50</td><td>79.42</td><td>76.04</td><td>-</td><td>-</td>
</tr>

<tr>
  <td><b>T4,5,6</b></td>
  <td>95.18</td><td>97.38</td><td>97.52</td>
  <td>76.32</td><td>86.05</td><td>85.04</td><td>86.1</td><td>88.0</td>
  <td>71.08</td><td>85.76</td><td>80.66</td><td>85.8</td><td>82.6</td>
  <td>61.28</td><td>75.82</td><td>72.36</td><td>75.8</td><td>72.8</td>
  <td>64.84</td><td>78.83</td><td>76.42</td><td>78.8</td><td>76.5</td>
  <td>46.40</td><td>65.99</td><td>59.73</td><td>66.0</td><td>59.4</td>
  <td>36.94</td><td>59.73</td><td>49.69</td><td>59.7</td><td>51.0</td>
  <td>59.04</td><td>76.17</td><td>71.59</td><td>-</td><td>-</td>
</tr>

<tr>
  <td><b>T1,3,5</b></td>
  <td>97.57</td><td>98.89</td><td>98.77</td>
  <td>79.13</td><td>87.73</td><td>87.73</td><td>87.7</td><td>89.2</td>
  <td>75.29</td><td>88.15</td><td>84.59</td><td>88.1</td><td>84.9</td>
  <td>63.75</td><td>78.07</td><td>74.76</td><td>78.1</td><td>74.0</td>
  <td>66.79</td><td>79.99</td><td>77.52</td><td>80.0</td><td>76.6</td>
  <td>52.84</td><td>69.73</td><td>65.88</td><td>69.7</td><td>65.1</td>
  <td>46.00</td><td>66.59</td><td>59.28</td><td>69.7</td><td>65.1</td>
  <td>63.90</td><td>79.03</td><td>75.90</td><td>79.0</td><td>74.5</td>
</tr>

<tr>
  <td><b>T2,4,6</b></td>
  <td>94.61</td><td>97.68</td><td>97.19</td>
  <td>79.02</td><td>87.49</td><td>87.49</td><td>88.0</td><td>89.1</td>
  <td>73.04</td><td>86.99</td><td>82.68</td><td>87.0</td><td>83.9</td>
  <td>60.68</td><td>76.51</td><td>71.99</td><td>76.5</td><td>72.7</td>
  <td>63.62</td><td>78.49</td><td>74.76</td><td>78.5</td><td>74.0</td>
  <td>47.38</td><td>68.51</td><td>61.15</td><td>68.5</td><td>59.8</td>
  <td>39.00</td><td>62.67</td><td>53.03</td><td>62.7</td><td>51.3</td>
  <td>59.93</td><td>77.73</td><td>72.80</td><td>77.7</td><td>71.0</td>
</tr>

  </tbody>
</table>


<h2> Turbidity Measurements </h2>

<table>
  <thead>
    <tr>
      <th>Turbidity Level</th>
      <th>Mean FTU</th>
      <th>Standard Deviation</th>
      <th>Absorbance (640 THz)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>T1</b></td>
      <td>0.028</td>
      <td>0.011</td>
      <td>0.00907</td>
    </tr>
    <tr>
      <td><b>T2</b></td>
      <td>0.710</td>
      <td>0.013</td>
      <td>0.00921</td>
    </tr>
    <tr>
      <td><b>T3</b></td>
      <td>1.210</td>
      <td>0.081</td>
      <td>0.00926</td>
    </tr>
    <tr>
      <td><b>T4</b></td>
      <td>1.589</td>
      <td>0.118</td>
      <td>0.00946</td>
    </tr>
    <tr>
      <td><b>T5</b></td>
      <td>2.084</td>
      <td>0.119</td>
      <td>0.00974</td>
    </tr>
    <tr>
      <td><b>T6</b></td>
      <td>2.541</td>
      <td>0.149</td>
      <td>0.00950</td>
    </tr>
  </tbody>
</table>


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


<h2>Synthetic vs Real – Turbidity Training Evaluation (25K iterations)</h2>

<table>
  <thead>
    <tr>
      <th rowspan="2">Training turbidity</th>
      <th colspan="3">Synthetic (25K) – Itself</th>
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
  </tbody>
</table>








<h2>Synthetic vs Real – Turbidity Training Evaluation (25K iterations)</h2>

<!-- ======================= TABLA 1: Synthetic + T1, T2, T3 ======================= -->
<div style="font-size: 11px;">
  <h3>Part 1 – Synthetic (25K) + T1, T2, T3 (real)</h3>
  <table>
    <thead>
      <tr>
        <th rowspan="2">Training turbidity</th>
        <th colspan="3">Synthetic (25K) – Itself</th>
        <th colspan="5">T1 (real)</th>
        <th colspan="5">T2 (real)</th>
        <th colspan="5">T3 (real)</th>
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
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><b>T1</b></td>
        <td>98.7</td><td>99.37</td><td>99.35</td>
        <td>70.81</td><td>83.00</td><td>78.96</td><td>83.0</td><td>84.8</td>
        <td>70.08</td><td>84.97</td><td>79.12</td><td>85.0</td><td>82.3</td>
        <td>58.66</td><td>74.35</td><td>69.86</td><td>74.4</td><td>68.7</td>
      </tr>
      <tr>
        <td><b>T2</b></td>
        <td>98.5</td><td>99.32</td><td>99.24</td>
        <td>76.46</td><td>86.11</td><td>85.64</td><td>86.1</td><td>87.7</td>
        <td>72.40</td><td>86.60</td><td>82.19</td><td>86.6</td><td>82.0</td>
        <td>58.55</td><td>74.01</td><td>69.84</td><td>74.0</td><td>68.3</td>
      </tr>
      <tr>
        <td><b>T3</b></td>
        <td>98.08</td><td>99.20</td><td>99.03</td>
        <td>75.89</td><td>86.49</td><td>84.69</td><td>87.6</td><td>86.5</td>
        <td>73.30</td><td>87.23</td><td>82.10</td><td>87.2</td><td>84.0</td>
        <td>62.83</td><td>78.49</td><td>75.53</td><td>78.5</td><td>72.3</td>
      </tr>
      <tr>
        <td><b>T4</b></td>
        <td>97.36</td><td>98.81</td><td>98.66</td>
        <td>80.10</td><td>88.65</td><td>88.38</td><td>88.6</td><td>89.7</td>
        <td>76.18</td><td>88.39</td><td>85.06</td><td>88.9</td><td>85.1</td>
        <td>59.76</td><td>76.16</td><td>71.62</td><td>76.2</td><td>69.8</td>
      </tr>
      <tr>
        <td><b>T5</b></td>
        <td>96.18</td><td>98.41</td><td>98.04</td>
        <td>81.57</td><td>89.69</td><td>89.49</td><td>89.7</td><td>90.2</td>
        <td>78.15</td><td>89.95</td><td>87.00</td><td>90.0</td><td>86.7</td>
        <td>65.55</td><td>80.06</td><td>77.17</td><td>80.1</td><td>75.9</td>
      </tr>
      <tr>
        <td><b>T6</b></td>
        <td>93.16</td><td>96.30</td><td>96.42</td>
        <td>68.32</td><td>82.44</td><td>78.74</td><td>82.4</td><td>79.3</td>
        <td>70.69</td><td>85.58</td><td>81.08</td><td>85.6</td><td>80.8</td>
        <td>54.41</td><td>72.32</td><td>66.55</td><td>72.3</td><td>66.7</td>
      </tr>
      <tr>
        <td><b>T1–6</b></td>
        <td>97.01</td><td>98.55</td><td>98.00</td>
        <td>78.59</td><td>87.80</td><td>87.05</td><td>87.8</td><td>88.3</td>
        <td>74.90</td><td>88.77</td><td>84.29</td><td>88.8</td><td>83.9</td>
        <td>64.21</td><td>79.84</td><td>75.85</td><td>79.8</td><td>74.9</td>
      </tr>
      <tr>
        <td><b>T1,2,3</b></td>
        <td>98.22</td><td>99.25</td><td>99.10</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
      </tr>
      <tr>
        <td><b>T2,3,4</b></td>
        <td>97.98</td><td>99.10</td><td>98.98</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
      </tr>
      <tr>
        <td><b>T3,4,5</b></td>
        <td>97.43</td><td>98.71</td><td>98.69</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
      </tr>
      <tr>
        <td><b>T4,5,6</b></td>
        <td>95.18</td><td>97.38</td><td>97.52</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
      </tr>
      <tr>
        <td><b>T1,3,5</b></td>
        <td>97.57</td><td>98.89</td><td>98.77</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
      </tr>
      <tr>
        <td><b>T2,4,6</b></td>
        <td>94.61</td><td>97.68</td><td>97.19</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
      </tr>
    </tbody>
  </table>

  <h3>Part 2 – T4, T5, T6 and T1–6 (real)</h3>
  <table>
    <thead>
      <tr>
        <th rowspan="2">Training turbidity</th>
        <th colspan="5">T4 (real)</th>
        <th colspan="5">T5 (real)</th>
        <th colspan="5">T6 (real)</th>
        <th colspan="5">T1–6 (real)</th>
      </tr>
      <tr>
        <-- T4 -->
        <th>mIoU</th><th>mAcc</th><th>mDice</th><th>mRec</th><th>mPrec</th>
        <-- T5 -->
        <th>mIoU</th><th>mAcc</th><th>mDice</th><th>mRec</th><th>mPrec</th>
        <-- T6 -->
        <th>mIoU</th><th>mAcc</th><th>mDice</th><th>mRec</th><th>mPrec</th>
        <-- T1–6 -->
        <th>mIoU</th><th>mAcc</th><th>mDice</th><th>mRec</th><th>mPrec</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><b>T1</b></td>
        <td>56.58</td><td>71.86</td><td>68.16</td><td>71.9</td><td>69.0</td>
        <td>42.31</td><td>56.88</td><td>55.13</td><td>56.9</td><td>61.3</td>
        <td>33.84</td><td>50.64</td><td>45.62</td><td>50.6</td><td>56.9</td>
        <td>59.75</td><td>74.97</td><td>71.20</td><td>75.0</td><td>71.1</td>
      </tr>
      <tr>
        <td><b>T2</b></td>
        <td>61.14</td><td>74.00</td><td>72.02</td><td>74.0</td><td>72.7</td>
        <td>44.94</td><td>57.27</td><td>57.44</td><td>57.3</td><td>63.0</td>
        <td>37.38</td><td>53.62</td><td>50.53</td><td>53.6</td><td>59.9</td>
        <td>62.81</td><td>76.69</td><td>74.50</td><td>76.7</td><td>74.3</td>
      </tr>
      <tr>
        <td><b>T3</b></td>
        <td>64.93</td><td>79.57</td><td>75.93</td><td>79.6</td><td>75.3</td>
        <td>47.36</td><td>67.64</td><td>60.32</td><td>67.6</td><td>60.4</td>
        <td>42.33</td><td>65.01</td><td>54.09</td><td>65.0</td><td>57.2</td>
        <td>60.53</td><td>78.04</td><td>72.60</td><td>78.0</td><td>72.5</td>
      </tr>
      <tr>
        <td><b>T4</b></td>
        <td>63.19</td><td>77.19</td><td>74.56</td><td>77.2</td><td>73.8</td>
        <td>48.64</td><td>65.83</td><td>61.42</td><td>65.8</td><td>62.6</td>
        <td>39.43</td><td>63.52</td><td>55.92</td><td>63.5</td><td>59.3</td>
        <td>61.41</td><td>77.49</td><td>73.70</td><td>77.5</td><td>72.1</td>
      </tr>
      <tr>
        <td><b>T5</b></td>
        <td>64.00</td><td>79.00</td><td>75.88</td><td>79.0</td><td>75.7</td>
        <td>53.06</td><td>71.08</td><td>66.24</td><td>71.1</td><td>66.3</td>
        <td>46.33</td><td>64.15</td><td>58.66</td><td>64.1</td><td>62.3</td>
        <td>64.15</td><td>79.81</td><td>76.50</td><td>79.8</td><td>75.0</td>
      </tr>
      <tr>
        <td><b>T6</b></td>
        <td>59.76</td><td>74.71</td><td>71.47</td><td>74.7</td><td>72.4</td>
        <td>44.02</td><td>63.03</td><td>57.02</td><td>63.0</td><td>57.4</td>
        <td>36.07</td><td>57.44</td><td>48.31</td><td>57.4</td><td>53.0</td>
        <td>55.02</td><td>73.65</td><td>68.10</td><td>73.6</td><td>67.0</td>
      </tr>
      <tr>
        <td><b>T1–6</b></td>
        <td>64.28</td><td>80.34</td><td>76.21</td><td>80.3</td><td>74.9</td>
        <td>51.34</td><td>70.50</td><td>64.10</td><td>70.5</td><td>61.5</td>
        <td>42.53</td><td>66.81</td><td>55.93</td><td>66.8</td><td>56.1</td>
        <td>66.35</td><td>82.03</td><td>77.80</td><td>82.0</td><td>76.0</td>
      </tr>
      <tr>
        <td><b>T1,2,3</b></td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
      </tr>
      <tr>
        <td><b>T2,3,4</b></td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
      </tr>
      <tr>
        <td><b>T3,4,5</b></td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
      </tr>
      <tr>
        <td><b>T4,5,6</b></td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
      </tr>
      <tr>
        <td><b>T1,3,5</b></td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
      </tr>
      <tr>
        <td><b>T2,4,6</b></td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
        <td>–</td><td>–</td><td>–</td><td>–</td><td>–</td>
      </tr>
    </tbody>
  </table>
</div>


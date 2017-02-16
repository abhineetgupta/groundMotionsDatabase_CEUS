# groundMotionsDatabase_CEUS
It contains a database of ground motion recordings for earthquakes in Central and Eastern United States. Spectral accelerations are calculated for 5% damped RotD50 component of horizontal time histories for all events with magnitudes ≥ 3 and epicentral distance ≤ 200 km from Jan 01, 2001 to Dec 31, 2016 for the CEUS region between 27° and 55° latitudes and -105° and -70° longitudes.

For details on data processing, refer to : Gupta, Baker, Ellsworth, Assessing ground motion amplitudes and attenuation for small to moderate induced and tectonic earthquakes in the Central and Eastern United States, 2017.

Individual original time histories can be requested by contacting the author.


% Files %%%%%%%%%%%%%%%%%%%%%%%%%

eqSpectraRotD50FilteredGMPE_ENA_Cleaned.csv 	 : Spectral accelerations for each recording without Vs30 correction.

eqSpectraRotD50FilteredGMPE_ENA_Cleaned_vs30.csv : Spectral accelerations for each recording at Vs30 = 760 m/s.

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


% Description of column headers %

RecordNumber     : record number

StationNetwork   : network of seismic station

StationName      : name of seismic station

StationChannel   : first two letters identify channel type. third alphabet is irrelevant since values are RotD50.

StationLatitude  : latitude of station

StationLongitude : longitude on station

StationYear      : year of earthquake occurrence

StationMonth     : month of earthquake occurrence

StationDay       : day of earthquake occurrence

StationHour      : hour of earthquake occurrence

StationMin       : minute of earthquake occurrence

StationSec       : second of earthquake occurrence

EQLatitude       : earthquake latitude

EQLongitude      : earthquake longitude

EQDepthm         : earthquake depth in meters

Magnitude        : earthquake magnitude

MagType          : magnitude scale

Distancekm       : distance between earthquake and station in kilometers

Filename         : filename that contained the original time history

PeriodApBC       : 5% damped RotD50 spectral acceleration in units of gravity acceleration (g) at period A.BC seconds. example, Period0p20 is acceleration at period = 0.20 sec

PGV				 : peak ground velocity in units of g-second.

Vs30			 : Vs30 value in meters/second

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

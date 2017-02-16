# groundMotionsDatabase_CEUS
It contains a database of ground motion recordings for earthquakes in Central and Eastern United States. Spectral accelerations are calculated for 5% damped RotD50 component of horizontal time histories for all events with magnitudes ≥ 3 and epicentral distance ≤ 200 km from Jan 01, 2001 to Dec 31, 2016 for the CEUS region between 27° and 55° latitudes and -105° and -70° longitudes.<br />
For details on data processing, refer to : Gupta, Baker, Ellsworth, Assessing ground motion amplitudes and attenuation for small to moderate induced and tectonic earthquakes in the Central and Eastern United States, 2017.<br />
Individual original time histories can be requested by contacting the author.


% Files %%%%%%%%%%%%%%%%%%%%%%%%%%%%<br />
eqSpectraRotD50FilteredGMPE_ENA_Cleaned.csv 	 : Spectral accelerations for each recording without Vs30 correction.<br />
eqSpectraRotD50FilteredGMPE_ENA_Cleaned_vs30.csv : Spectral accelerations for each recording at Vs30 = 760 m/s.<br />
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


% Description of column headers %%%%%%%%%%%%%<br />
RecordNumber     : record number<br />
StationNetwork   : network of seismic station<br />
StationName      : name of seismic station<br />
StationChannel   : first two letters identify channel type. third alphabet is irrelevant since values are RotD50.<br />
StationLatitude  : latitude of station<br />
StationLongitude : longitude on station<br />
StationYear      : year of earthquake occurrence<br />
StationMonth     : month of earthquake occurrence<br />
StationDay       : day of earthquake occurrence<br />
StationHour      : hour of earthquake occurrence<br />
StationMin       : minute of earthquake occurrence<br />
StationSec       : second of earthquake occurrence<br />
EQLatitude       : earthquake latitude<br />
EQLongitude      : earthquake longitude<br />
EQDepthm         : earthquake depth in meters<br />
Magnitude        : earthquake magnitude<br />
MagType          : magnitude scale<br />
Distancekm       : distance between earthquake and station in kilometers<br />
Filename         : filename that contained the original time history<br />
PeriodApBC       : 5% damped RotD50 spectral acceleration in units of gravity acceleration (g) at period A.BC seconds. example, Period0p20 is acceleration at period = 0.20 sec<br />
PGV				 : peak ground velocity in units of g-second.<br />
Vs30			 : Vs30 value in meters/second<br />
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

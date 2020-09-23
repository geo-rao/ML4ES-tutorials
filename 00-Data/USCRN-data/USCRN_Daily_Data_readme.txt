Field#  Name                           Units
---------------------------------------------
   1    WBANNO                         XXXXX
   2    LST_DATE                       YYYYMMDD
   3    CRX_VN                         XXXXXX
   4    LONGITUDE                      Decimal_degrees
   5    LATITUDE                       Decimal_degrees
   6    T_DAILY_MAX                    Celsius
   7    T_DAILY_MIN                    Celsius
   8    T_DAILY_MEAN                   Celsius
   9    T_DAILY_AVG                    Celsius
   10   P_DAILY_CALC                   mm
   11   SOLARAD_DAILY                  MJ/m^2
   12   SUR_TEMP_DAILY_TYPE            X
   13   SUR_TEMP_DAILY_MAX             Celsius
   14   SUR_TEMP_DAILY_MIN             Celsius
   15   SUR_TEMP_DAILY_AVG             Celsius
   16   RH_DAILY_MAX                   %
   17   RH_DAILY_MIN                   %
   18   RH_DAILY_AVG                   %
   19   SOIL_MOISTURE_5_DAILY          m^3/m^3
   20   SOIL_MOISTURE_10_DAILY         m^3/m^3
   21   SOIL_MOISTURE_20_DAILY         m^3/m^3
   22   SOIL_MOISTURE_50_DAILY         m^3/m^3
   23   SOIL_MOISTURE_100_DAILY        m^3/m^3
   24   SOIL_TEMP_5_DAILY              Celsius
   25   SOIL_TEMP_10_DAILY             Celsius
   26   SOIL_TEMP_20_DAILY             Celsius
   27   SOIL_TEMP_50_DAILY             Celsius
   28   SOIL_TEMP_100_DAILY            Celsius

   1    WBANNO: The station WBAN number.

   2    LST_DATE: The Local Standard Time (LST) date of the observation.

   3    CRX_VN: The version number of the station datalogger program that was in 
          effect at the time of the observation. Note: This field should be 
          treated as text (i.e. string).

   4    LONGITUDE: Station longitude, using WGS-84.

   5    LATITUDE: Station latitude, using WGS-84.

   6    T_DAILY_MAX: Maximum air temperature, in degrees C. See Note F.

   7    T_DAILY_MIN: Minimum air temperature, in degrees C. See Note F.

   8    T_DAILY_MEAN: Mean air temperature, in degrees C, calculated using the typical 
          historical approach: (T_DAILY_MAX + T_DAILY_MIN) / 2. See Note F.

   9    T_DAILY_AVG: Average air temperature, in degrees C. See Note F.

   10   P_DAILY_CALC: Total amount of precipitation, in mm. See Note F.

   11   SOLARAD_DAILY: Total solar energy, in MJ/meter^2, calculated from the hourly average 
          global solar radiation rates and converted to energy by integrating 
          over time.

   12   SUR_TEMP_DAILY_TYPE: Type of infrared surface temperature measurement. 'R' denotes raw 
          measurements, 'C' denotes corrected measurements, and 'U' indicates 
          unknown/missing. See Note G.

   13   SUR_TEMP_DAILY_MAX: Maximum infrared surface temperature, in degrees C.

   14   SUR_TEMP_DAILY_MIN: Minimum infrared surface temperature, in degrees C.

   15   SUR_TEMP_DAILY_AVG: Average infrared surface temperature, in degrees C.

   16   RH_DAILY_MAX: Maximum relative humidity, in %. See Notes H and I.

   17   RH_DAILY_MIN: Minimum relative humidity, in %. See Notes H and I.

   18   RH_DAILY_AVG: Average relative humidity, in %. See Notes H and I.

   19   SOIL_MOISTURE_5_DAILY: Average soil moisture, in fractional volumetric water content (m^3/m^3), 
          at 5 cm below the surface. See Notes I and J.

   20   SOIL_MOISTURE_10_DAILY: Average soil moisture, in fractional volumetric water content (m^3/m^3), 
          at 10 cm below the surface. See Notes I and J.

   21   SOIL_MOISTURE_20_DAILY: Average soil moisture, in fractional volumetric water content (m^3/m^3), 
          at 20 cm below the surface. See Notes I and J.

   22   SOIL_MOISTURE_50_DAILY: Average soil moisture, in fractional volumetric water content (m^3/m^3), 
          at 50 cm below the surface. See Notes I and J.

   23   SOIL_MOISTURE_100_DAILY: Average soil moisture, in fractional volumetric water content (m^3/m^3), 
          at 100 cm below the surface. See Notes I and J.

   24   SOIL_TEMP_5_DAILY: Average soil temperature, in degrees C, at 5 cm below the surface. 
          See Notes I and J.

   25   SOIL_TEMP_10_DAILY: Average soil temperature, in degrees C, at 10 cm below the surface. 
          See Notes I and J.

   26   SOIL_TEMP_20_DAILY: Average soil temperature, in degrees C, at 20 cm below the surface. 
          See Notes I and J.

   27   SOIL_TEMP_50_DAILY: Average soil temperature, in degrees C, at 50 cm below the surface. 
          See Notes I and J.

   28   SOIL_TEMP_100_DAILY: Average soil temperature, in degrees C, at 100 cm below the surface. 
          See Notes I and J.

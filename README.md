# utl-gis-download-all-the-census_2023-tiger-line-files
GIS download all the census 2023 tiger line files. The result is 49 zip files instead of ~20,000 zip files (small 16gb)
    %let pgm=utl-gis-download-all-the-census_2023-tiger-line-files;

    GIS download all the census 2023 tiger line files. The result is 49 zip files instead of ~20,000 zip files (small 16gb)

    If you want just the zipcode single map file maps
    www2.census.gov/geo/tiger/TIGER2023/ZCTA520/
    tl_2023_us_zcta520.zip

    However if you want ALL the tiger line files use  (you need 7zip)
    Also open withn options 'open archive' and select the fike you want ro unzip.

    Link good for 2years
    https://1drv.ms/u/s!AovFHZtMPA-7gmIV-TVa7zi5RqNR?e=hUM98j `7gb

    Instead of downloading more than 20,000 tiny zip files you only have to download 49 7 zip
    files. Another advantage is the 7 zip files are up to 50% smaller than the original zip files.

    /********************************************************************************************************************************************/
    /*                                                                                                                                          */
    /* For example when you unzip  EDGE you get one file instead of 3,325 files                                                                 */
    /*                                                                                                                                          */
    /*  SHORT                   ONEDRIVEFILE                          LONG_DESCRIPTION                                               SIZE       */
    /*                                                                                                                                          */
    /*  ADDR                    tl_2023_xxxxx_addr.exe                Address Range Relationship File                             346,377,028   */
    /*  ADDRFEAT                tl_2023_xxxxx_addrfeat.exe            Address Range Feature                                     1,396,002,806   */
    /*  ADDRFN                  tl_2023_xxxxx_addrfn.exe              Address Range-Feature Name Relationship                     180,974,965   */
    /*  AIANN                   tl_2023_us_aiann.exe                  American Indian / Alaska Native / Native Hawaiian Areas       3,944,839   */
    /*  AITSN                   tl_2023_us_aitsn.exe                  American Indian Tribal Subdivision National                   2,428,787   */
    /*  ANRC       cartographic tl_2023_02_anrc.exe                   Alaska Native Regional Corporation                              509,635   */
    /*  AREALM                  tl_2023_xx_arealm.exe                 Area Landmark                                                28,426,443   */
    /*  AREAWATER               tl_2023_xxxxx_areawater.exe           Area Hydrography                                            522,193,719   */
    /*  BG         cartographic tl_2023_xx_bg.exe__                   Block Group                                                 242,318,904   */
    /*  CBSA       cartographic tl_2023_us_cbsa.exe                   Core Based Statistical Area                                  12,789,538   */
    /*  CD         cartographic tl_2023_xx_cd.exe__                   118th Congressional District                                 12,698,376   */
    /*  COASTLINE               tl_2023_coastline.exe                 Coastline                                                     6,901,030   */
    /*  CONCITY                 tl_2023_xx_concity.exe                Consolidated City                                               352,700   */
    /*  COUNTY     cartographic tl_2023_us_county.exe                 County                                                       30,118,829   */
    /*  COUSUB     cartographic tl_2023_xx_cousub.exe                 County Subdivision                                           99,582,239   */
    /*  CSA        cartographic tl_2023_us_csa.exe_                   Combined Statistical Area                                     5,176,549   */
    /*  EDGE                    tl_2023_xxxxx_edge.exe                All Lines                                                 5,204,395,872   */
    /*  ELSD                    tl_2023_xx_elsd.exe                   Elementary School District                                    5,229,157   */
    /*  ESTATE                  tl_2023_78_estate.exe                 Estate                                                          507,299   */
    /*  FACEMIL                 tl_2023_us_facemil.exe                Topological Faces-Military Installation Relationship File       462,374   */
    /*  FACES                   tl_2023_xxxxx_faces.exe               Topological Faces (Polygons with All Geocodes)            4,153,445,826   */
    /*  FACESAH                 tl_2023_xxxxx_facesah.exe             Topological Faces-Area Hydrography Relationship File         11,033,044   */
    /*  FACESAL                 tl_2023_xx_facesal.exe                Topological Faces-Area Landmark Relationship File             2,030,701   */
    /*  FEATNAMES               tl_2023_xxxxx_featnames.exe           Feature Names Relationship File                             592,174,539   */
    /*  INTERNATIONALBOUNDARY   tl_2023_us_internationalboundary.exe  International Boundaries                                        633,125   */
    /*  LINEARWATER             tl_2023_xxxxx_linearwater.exe         Linear Hydrography                                          819,542,628   */
    /*  METDIV                  tl_2023_us_metdiv.exe                 Metropolitan Division                                         1,110,458   */
    /*  MIL                     tl_2023_us_mil.exe_                   Military Installation                                         1,535,879   */
    /*  PLACE      cartographic tl_2023_xx_place.exe                  Place                                                        58,971,360   */
    /*  POINTLM                 tl_2023_xx_pointlm.exe                Point Landmark                                               14,795,294   */
    /*  PRIMARYROADS            tl_2023_us_primaryroads.exe           Primary Roads                                                10,864,705   */
    /*  PRISECROADS             tl_2023_xx_prisecroads.exe            Primary and Secondary Roads                                  81,736,338   */
    /*  PUMA20     cartographic tl_2023_xx_puma20.exe                 2020 Public Use Microdata Area                               22,919,653   */
    /*  RAILS                   tl_2023_us_rails.exe                  Rails                                                        14,443,076   */
    /*  ROADS                   tl_2023_xxxxx_roads.exe               All Roads                                                 1,700,817,692   */
    /*  SCSD                    tl_2023_xx_scsd.exe                   Secondary School Districts                                    2,996,132   */
    /*  SDADM                   tl_2023_50_sdadm.exe                  Administrative School Districts                                 412,798   */
    /*  SLDL       cartographic tl_2023_xx_sldl.exe                   State Legislative District – Lower Chamber                   37,948,542   */
    /*  SLDU       cartographic tl_2023_xx_sldu.exe                   State Legislative District – Upper Chamber                   26,051,832   */
    /*  STATE      cartographic tl_2023_us_state.exe                  State and Equivalent                                          3,446,504   */
    /*  SUBBARRIO               tl_2023_72_subbarrio.exe              SubMinor Civil Division (Subbarios in Puerto Rico)              291,333   */
    /*  TABBLOCK20              tl_2023_xx_tabblock20.exe             2020 Tabulation (Census) Block                            2,590,421,350   */
    /*  TBG                     tl_2023_us_tbg.exe_                   Tribal Block Group                                            4,148,162   */
    /*  TRACT      cartographic tl_2023_xx_tract.exe                  Census Tract                                                319,821,446   */
    /*  TTRACT     cartographic tl_2023_us_ttract.exe                 Tribal Census Tract                                           3,137,073   */
    /*  UAC20                   tl_2023_us_uac20.exe                  2020 Urban Area/Urban Cluster                                30,383,817   */
    /*  UNSD       cartographic tl_2023_xx_unsd.exe                   Unified School District                                      50,935,620   */
    /*  ZCTA520    cartographic tl_2023_us_zcta520.exe                2020 5-Digit ZIP Code Tab                                   178,988,996   */
    /*                                                                                                                                          */
    /********************************************************************************************************************************************/

    /*                              _
      _____  ____ _ _ __ ___  _ __ | | ___   _   _ ___  ___
     / _ \ \/ / _` | `_ ` _ \| `_ \| |/ _ \ | | | / __|/ _ \
    |  __/>  < (_| | | | | | | |_) | |  __/ | |_| \__ \  __/
     \___/_/\_\__,_|_| |_| |_| .__/|_|\___|  \__,_|___/\___|
                             |_|
    */
    There are many more exaples using rnaturalearth

    https://www2.census.gov/geo/tiger/TIGER2023
    https://biostats-r.github.io/biostats/workingInR/140_maps.html
    https://cran.r-project.org/src/contrib/Archive/USAboundaries/
    https://cran.r-project.org/web/packages/rnaturalearth/index.html
    https://github.com/ropensci
    https://github.com/walkerke/tigris/tree/master
    https://public.opendatasoft.com/explore/dataset/natural-earth-countries-1_110m/table/
    https://r-spatial.org/r/2018/10/25/ggplot2-sf-2.html
    https://r-spatial.org/r/2018/10/25/ggplot2-sf.html
    https://ryanpeek.org/2019-04-29-spatial-joins-in-r/
    https://stackoverflow.com/questions/69540839/convert-sf-object-to-dataframe-and-restore-it-to-original-state
    https://stackoverflow.com/questions/73028127/adding-coordinates-as-points-to-a-map-in-r
    https://walker-data.com/census-r/census-geographic-data-and-applications-in-r.html
    https://walker-data.com/census-r/mapping-census-data-with-r.html
    https://www.rdocumentation.org/packages/rnaturalearth/versions/0.3.4/topics/ne_countries

    /*              _
      ___ _ __   __| |
     / _ \ `_ \ / _` |
    |  __/ | | | (_| |
     \___|_| |_|\__,_|

    */

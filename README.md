╔══════════════════════════════════════════════════════════╗ ║ Sinisa Svoger 30.4.2026. 
TERMINAL :: MATERIAL ANALYSIS MODULE v1.0 ║ ║ CLASSIFIED ENGINEERING
INTERFACE ║ ╚══════════════════════════════════════════════════════════╝

  INITIALIZING SYSTEM… LOADING STRUCTURAL ANALYSIS PROTOCOL… READY.

  -----------------------------------------------
  [ MODULE ] : MODULUS OF ELASTICITY CALCULATOR
  -----------------------------------------------
Project assignment
It is necessary to develop a program that calculates the modulus of elasticity (E). 
The program should accept lattice stress and lattice strain as input values.
Next, the program should generate a diagram with lattice strain plotted on the x-axis and lattice stress on the y-axis, forming a curve that represents their relationship.
From the initial linear portion of this curve, two points should be selected. A straight line should then be drawn through these points.
Finally, the modulus of elasticity (E) should be calculated using the slope of the line defined by the selected two points.
There are two version with different GUI: Classic nad retro gaming 


:: INPUT PARAMETERS ::

    LATTICE STRAIN (ε) : ARRAY[ n ] LATTICE STRESS (σ) : ARRAY[ n ]

CONSTRAINTS: - INPUT LENGTH MUST MATCH - MINIMUM DATA POINTS: 2 -
NUMERIC VALUES ONLY

  ------------------------------------------------------------
  :: PROCESS SEQUENCE ::
  ------------------------------------------------------------
  [01] VALIDATE INPUT DATA [02] GENERATE STRESS-STRAIN GRAPH
  [03] IDENTIFY INITIAL LINEAR REGION [04] SELECT TWO POINTS
  (USER/AUTO) [05] DRAW LINE THROUGH POINTS [06] CALCULATE
  ELASTIC MODULUS

  ------------------------------------------------------------

:: CORE EQUATION ::

E = (σ2 - σ1) / (ε2 - ε1)

    SLOPE OF LINE = ELASTIC MODULUS

  ------------------------------------------------------------
  :: VISUAL OUTPUT ::
  ------------------------------------------------------------
  DISPLAY: - STRESS (Y-AXIS) - STRAIN (X-AXIS) - CURVE
  PROFILE - SELECTED POINTS - LINEAR APPROXIMATION VECTOR

  ------------------------------------------------------------

:: SYSTEM OUTPUT ::

    ELASTIC MODULUS (E) COMPUTED GRAPHICAL ANALYSIS COMPLETE

  ------------------------------------------------------------
  :: OPTIONAL EXTENSIONS ::
  ------------------------------------------------------------
  + AUTO LINEAR REGRESSION + DATA EXPORT (CSV / TXT) + GRAPH
  EXPORT (PNG) + MULTI-SAMPLE ANALYSIS

  ------------------------------------------------------------

:: STATUS ::

  SYSTEM STABLE NO ERRORS DETECTED READY FOR DEPLOYMENT

╔══════════════════════════════════════════════════════════╗ ║ END OF
TRANSMISSION ║
╚══════════════════════════════════════════════════════════╝

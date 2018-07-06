QuB scripts are '.kin' files that can only be read by QuB, '.txt' versions are included for convenience



QuB DC code is written in Kinetic Progrmaming Language (KPL)
https://milesculabs.biology.missouri.edu/QuB_KPL.html




-----------------------------------------------------------------
General Script structure		Commands/Syntax of Note
-----------------------------------------------------------------

Simulation/DClamp mode setup		vread, mcell




Model parameters & equations		par, var, =, :=					<-- BEATING HEART OF MODEL SCRIPTS





ODE object declaration			odesys ode;

Hardware I/O & files			includefile
					amplifier_cal.kin, amplifier_io.kin
					ode.idevicename, ode.odevicename

Graphical Output			ode.addout()


Real time ODE Solver			ode.solvert()


-----------------------------------------------------------------
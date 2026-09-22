# Autocross Event

### D6.1 Autocross Track Layout

##### D6.1.1

> The autocross track layout is a handling track built to the following guidelines:
> - Straights: No longer than 80m,
> - Constant Turns: up to 50m diameter,
> - Hairpin Turns: Minimum of 9m outside diameter (of the turn),
> - Slaloms: Cones in a straight line with 7.5m to 12m spacing,
> - Miscellaneous: Chicanes, multiple turns, decreasing radius turns, etc. The minimum
> track width is 3 m.

##### D6.1.2

> The length of the autocross track is less than 1.5km.

##### D6.1.3

> [DC ONLY] The autocross is using the same track as the trackdrive event (see D8.1).

##### D6.1.4

> The organisers reserve the right to deviate from the parameters specified when they
> determine it is appropriate given the characteristics of the particular competition site.

### D6.2 Autocross Procedure

##### D6.2.1

> Each team has four initial runs, driven by two drivers with two runs each.

##### D6.2.2

> Each driver has the option to make a second run immediately after their first run.

##### D6.2.3

> Following completion of the four initial runs, both drivers can continue to run for an
> unlimited number of laps. Each additional lap will replace that driver’s fastest previous lap
> time, excluding any penalties.

##### D6.2.4

> Staging - The vehicle is staged at a staging line prior to the starting line. The staging line
> will be a minimum of 2m from the start line and a maximum of 6m, cars will be positioned
> on this line by the marshals.

##### D6.2.5

> Starting - A green flag is used to indicate that the driver may start. Timing starts only after
> the vehicle crosses the starting line and stops after it crosses the finish line.

##### D6.2.6

> The starting order is based on the time the team arrives at the autocross event. Teams
> will be prioritised as follows:
> - Teams on their first run.
> - Teams on runs 2 to 4.
> - Teams on run 5 onwards.

##### D6.2.7

> If a stalled or broken-down vehicle is blocking the track, then all other vehicles on track
> will be shown the red flag and allowed another run.

### D6.3 [DC ONLY] Driverless Autocross Procedure

##### D6.3.1

> There will be a track walk prior to the autocross. During the track walk no equipment (e.g.
> antennas, sensors, cameras, etc) other than analogue measurement devices (i.e.
> measurement wheel or measurement tape) is allowed.

##### D6.3.2

> Using data collected in a previous run is not permitted for the autocross event.

##### D6.3.3

> Each team has at least two runs consisting of one single lap. The final number of runs will
> be published before the start of the event.

##### D6.3.4

> The starting order is based on the time the team arrives at the autocross event. Teams on
> their first run will receive priority.

##### D6.3.5

> Staging - The vehicle is staged such that the front wheels are 6m in front of the starting
> line on the track.

##### D6.3.6

> Starting - A go-signal from RES is used to indicate the approval to begin. Timing starts
> after the vehicle crosses the starting line.

##### D6.3.7

> After the run, the vehicle must come to a full stop within 30m behind the finish line on
> the track and enter the finish-state described in T14.9.

### D6.4 Autocross Scoring

##### D6.4.1

> 5 points are awarded to every team that finishes at least one run without DNF or DQ.

##### D6.4.2

> If a team’s corrected elapsed time is below Tmax, points based on the following formula are
> given:
>
> \[
> \textit{AUTOCROSS SCORE} = 95\left(\frac{\frac{T_{max}}{T_{team}} - 1}{\frac{T_{max}}{T_{min}} - 1}\right)
> \]
>
>
> - Tteam is the team’s best time including penalties.
> - Tmin is the fastest vehicle time including penalties.
> - Tmax is 145% of the fastest vehicle time including penalties.

### D6.5 [DC ONLY] Driverless Autocross Scoring

##### D6.5.1

> 10 points are awarded to every team that finishes at least one run without DNF or DQ.

##### D6.5.2

> If a team’s corrected elapsed time is below Tmax, points based on the following formula are
> given:
>
> \[
> \textit{AUTOCROSS\_SCORE}_{i} = 90\left(\frac{T_{max} - T_{team,i}}{T_{max} - T_{min}}\right)
> \]
>
> \[
> \textit{AUTOCROSS\_SCORE}_{total}
> = max(\textit{AUTOCROSS\_SCORE}_{1}, avg(\textit{AUTOCROSS\_SCORE}_{1}..\textit{AUTOCROSS\_SCORE}_{n}))
> \]
>
>
> - Tteam,i is the team’s time including penalties of run i.
> - Tmax is the time for driving the lap with 4m/s.
> - Tmin is the fastest corrected elapsed time of all teams.

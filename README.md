# Wind_mill_power_generate
<p><strong>Predict the power that us generated(in KW/h) by wind turbines.</strong></p>

<h2><strong>Data description</strong></h2>
<p> The dataset folder contains the follwoing files</p>
<ol>
	<li><strong>train.csv</strong>: 28200 x 22</li>
	<li><strong>test.csv</strong>: 12086 x 21</li>
</ol>

<p>The dataset contains the following columns:</p>

<table border="1" style="width:605px">
	<tbody>
		<tr>
			<td style="text-align:center; width:220px"><strong>Column name</strong></td>
			<td style="text-align:center; width:370px"><strong>Description</strong></td>
		</tr>
		<tr>
			<td style="text-align:center; width:220px">tracking_id</td>
			<td style="width:370px">Represents a unique identification number of a windmill</td>
		</tr>
		<tr>
			<td style="text-align:center; width:220px">datetime</td>
			<td style="width:370px">Represents the date and time of a record</td>
		</tr>
		<tr>
			<td style="text-align:center; width:220px">wind_speed(m/s)</td>
			<td style="width:370px">Represents the speed of wind (in meter per second)</td>
		</tr>
		<tr>
			<td style="text-align:center; width:220px">atmospheric_temperature(°C)</td>
			<td style="width:370px">Represents the temperature (in degree Celcius) of a town or village that the windmill is present in</td>
		</tr>
		<tr>
			<td style="text-align:center; width:220px">shaft_temperature(°C)</td>
			<td style="width:370px">Represents the temperature of the shaft (in degree Celcius)&nbsp;</td>
		</tr>
		<tr>
			<td style="text-align:center; width:220px">blades_angle(°)</td>
			<td style="width:370px">Represents the angle of the blades of a wind turbine (in degrees)</td>
		</tr>
		<tr>
			<td style="text-align:center; width:220px">gearbox_temperature(°C)</td>
			<td style="width:370px">Represents the temperature of a gearbox&nbsp; (in degree Celcius)</td>
		</tr>
		<tr>
			<td style="text-align:center; width:220px">engine_temperature(°C)</td>
			<td style="width:370px">Represents the temperature of an engine (in degree Celcius)</td>
		</tr>
		<tr>
			<td style="text-align:center; width:220px">motor_torque(N-m)</td>
			<td style="width:370px">Represents the torque of a motor (in Newton meter)</td>
		</tr>
		<tr>
			<td style="text-align:center; width:220px">generator_temperature(°C)</td>
			<td style="width:370px">Represents the temperature of a generator (in degree Celcius)</td>
		</tr>
		<tr>
			<td style="text-align:center; width:220px">atmospheric_pressure(Pascal)</td>
			<td style="width:370px">Represents the atmospheric pressure (in Pascals) in that area</td>
		</tr>
		<tr>
			<td style="text-align:center; width:220px">area_temperature(°C)</td>
			<td style="width:370px">Represents the temperature (in degree Celcius) of the area within a 100 m radius of the windmill</td>
		</tr>
		<tr>
			<td style="text-align:center; width:220px">windmill_body_temperature(°C)</td>
			<td style="width:370px">Represents the temperature of the body of a windmill (in degree Celcius)</td>
		</tr>
		<tr>
			<td style="text-align:center; width:220px">wind_direction(°)</td>
			<td style="width:370px">Represents the direction of the wind (in degrees)</td>
		</tr>
		<tr>
			<td style="text-align:center; width:220px">resistance(ohm)</td>
			<td style="width:370px">Represents the resistance against the wind</td>
		</tr>
		<tr>
			<td style="text-align:center; width:220px">rotor_torque(N-m)</td>
			<td style="width:370px">Represents the torque of a rotor (in Newton meter)</td>
		</tr>
		<tr>
			<td style="text-align:center; width:220px">turbine_status</td>
			<td style="width:370px">Represents the status of the turbine (masked)</td>
		</tr>
		<tr>
			<td style="text-align:center; width:220px">cloud_level</td>
			<td style="width:370px">
			<p>Represents the following levels of the cloud in the sky on a particular day:</p>
			<ul>
				<li>Extremely low</li>
				<li>Low</li>
				<li>Medium</li>
			</ul>
			</td>
		</tr>
		<tr>
			<td style="text-align:center; width:220px">blade_length(m)</td>
			<td style="width:370px">Represents the length of the blades of a windmill (in meter)</td>
		</tr>
		<tr>
			<td style="text-align:center; width:220px">blade_breadth(m)</td>
			<td style="width:370px">Represents the breadth of the blades of a windmill (in meter)</td>
		</tr>
		<tr>
			<td style="text-align:center; width:220px">windmill_height(m)</td>
			<td style="width:370px">Represents the height of the blades of a windmill (in meter)</td>
		</tr>
		<tr>
			<td style="text-align:center; width:220px">windmill_generated_power(kW/h)</td>
			<td style="width:370px">Represents the power generated (in Kilo Watt per hour)</td>
		</tr>
	</tbody>
</table>

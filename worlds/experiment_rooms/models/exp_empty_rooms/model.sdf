<?xml version="1.0" ?>
<sdf version="1.5">
  <model name="exp_empty_rooms">
    <light name='sun' type='directional'>
      <cast_shadows>1</cast_shadows>
      <pose frame=''>0 0 10 0 -0 0</pose>
      <diffuse>0.8 0.8 0.8 1</diffuse>
      <specular>0.2 0.2 0.2 1</specular>
      <attenuation>
        <range>1000</range>
        <constant>0.9</constant>
        <linear>0.01</linear>
        <quadratic>0.001</quadratic>
      </attenuation>
      <direction>-0.5 0.1 -0.9</direction>
    </light>
    <model name='ground_plane'>
      <static>1</static>
      <link name='link'>
        <collision name='collision'>
          <geometry>
            <plane>
              <normal>0 0 1</normal>
              <size>100 100</size>
            </plane>
          </geometry>
          <surface>
            <friction>
              <ode>
                <mu>100</mu>
                <mu2>50</mu2>
              </ode>
              <torsional>
                <ode/>
              </torsional>
            </friction>
            <contact>
              <ode/>
            </contact>
            <bounce/>
          </surface>
          <max_contacts>10</max_contacts>
        </collision>
        <visual name='visual'>
          <cast_shadows>0</cast_shadows>
          <geometry>
            <plane>
              <normal>0 0 1</normal>
              <size>100 100</size>
            </plane>
          </geometry>
          <material>
            <script>
              <uri>file://media/materials/scripts/gazebo.material</uri>
              <name>Gazebo/Grey</name>
            </script>
          </material>
        </visual>
        <self_collide>0</self_collide>
        <enable_wind>0</enable_wind>
        <kinematic>0</kinematic>
      </link>
    </model>
    <gravity>0 0 -9.8</gravity>
    <magnetic_field>6e-06 2.3e-05 -4.2e-05</magnetic_field>
    <atmosphere type='adiabatic'/>
    <physics name='default_physics' default='0' type='ode'>
      <max_step_size>0.001</max_step_size>
      <real_time_factor>1</real_time_factor>
      <real_time_update_rate>1000</real_time_update_rate>
    </physics>
    <scene>
      <ambient>0.4 0.4 0.4 1</ambient>
      <background>0.7 0.7 0.7 1</background>
      <shadows>1</shadows>
    </scene>
    <audio>
      <device>default</device>
    </audio>
    <wind/>
    <spherical_coordinates>
      <surface_model>EARTH_WGS84</surface_model>
      <latitude_deg>0</latitude_deg>
      <longitude_deg>0</longitude_deg>
      <elevation>0</elevation>
      <heading_deg>0</heading_deg>
    </spherical_coordinates>
    <model name='exp_empty_rooms'>
      <pose frame=''>0.98441 -0.690645 0 0 -0 0</pose>
      <link name='Wall_0'>
        <collision name='Wall_0_Collision'>
          <geometry>
            <box>
              <size>5 0.15 0.5</size>
            </box>
          </geometry>
          <pose frame=''>0 0 0.25 0 -0 0</pose>
          <max_contacts>10</max_contacts>
          <surface>
            <contact>
              <ode/>
            </contact>
            <bounce/>
            <friction>
              <torsional>
                <ode/>
              </torsional>
              <ode/>
            </friction>
          </surface>
        </collision>
        <visual name='Wall_0_Visual'>
          <pose frame=''>0 0 0.25 0 -0 0</pose>
          <geometry>
            <box>
              <size>5 0.15 0.5</size>
            </box>
          </geometry>
          <material>
            <script>
              <uri>file://media/materials/scripts/gazebo.material</uri>
              <name>Gazebo/Grey</name>
            </script>
            <ambient>1 1 1 1</ambient>
          </material>
          <meta>
            <layer>0</layer>
          </meta>
        </visual>
        <pose frame=''>-14.925 0 0 0 -0 -1.5708</pose>
        <self_collide>0</self_collide>
        <enable_wind>0</enable_wind>
        <kinematic>0</kinematic>
      </link>
      <link name='Wall_1'>
        <collision name='Wall_1_Collision'>
          <geometry>
            <box>
              <size>30 0.15 0.5</size>
            </box>
          </geometry>
          <pose frame=''>0 0 0.25 0 -0 0</pose>
          <max_contacts>10</max_contacts>
          <surface>
            <contact>
              <ode/>
            </contact>
            <bounce/>
            <friction>
              <torsional>
                <ode/>
              </torsional>
              <ode/>
            </friction>
          </surface>
        </collision>
        <visual name='Wall_1_Visual'>
          <pose frame=''>0 0 0.25 0 -0 0</pose>
          <geometry>
            <box>
              <size>30 0.15 0.5</size>
            </box>
          </geometry>
          <material>
            <script>
              <uri>file://media/materials/scripts/gazebo.material</uri>
              <name>Gazebo/Grey</name>
            </script>
            <ambient>1 1 1 1</ambient>
          </material>
          <meta>
            <layer>0</layer>
          </meta>
        </visual>
        <pose frame=''>0 -2.425 0 0 -0 0</pose>
        <self_collide>0</self_collide>
        <enable_wind>0</enable_wind>
        <kinematic>0</kinematic>
      </link>
      <link name='Wall_10'>
        <collision name='Wall_10_Collision'>
          <geometry>
            <box>
              <size>2.25 0.15 0.5</size>
            </box>
          </geometry>
          <pose frame=''>0 0 0.25 0 -0 0</pose>
          <max_contacts>10</max_contacts>
          <surface>
            <contact>
              <ode/>
            </contact>
            <bounce/>
            <friction>
              <torsional>
                <ode/>
              </torsional>
              <ode/>
            </friction>
          </surface>
        </collision>
        <visual name='Wall_10_Visual'>
          <pose frame=''>0 0 0.25 0 -0 0</pose>
          <geometry>
            <box>
              <size>2.25 0.15 0.5</size>
            </box>
          </geometry>
          <material>
            <script>
              <uri>file://media/materials/scripts/gazebo.material</uri>
              <name>Gazebo/Grey</name>
            </script>
            <ambient>1 1 1 1</ambient>
          </material>
          <meta>
            <layer>0</layer>
          </meta>
        </visual>
        <pose frame=''>-5.055 1.375 0 0 -0 -1.5708</pose>
        <self_collide>0</self_collide>
        <enable_wind>0</enable_wind>
        <kinematic>0</kinematic>
      </link>
      <link name='Wall_11'>
        <collision name='Wall_11_Collision'>
          <geometry>
            <box>
              <size>0.5 0.15 0.5</size>
            </box>
          </geometry>
          <pose frame=''>0 0 0.25 0 -0 0</pose>
          <max_contacts>10</max_contacts>
          <surface>
            <contact>
              <ode/>
            </contact>
            <bounce/>
            <friction>
              <torsional>
                <ode/>
              </torsional>
              <ode/>
            </friction>
          </surface>
        </collision>
        <visual name='Wall_11_Visual'>
          <pose frame=''>0 0 0.25 0 -0 0</pose>
          <geometry>
            <box>
              <size>0.5 0.15 0.5</size>
            </box>
          </geometry>
          <material>
            <script>
              <uri>file://media/materials/scripts/gazebo.material</uri>
              <name>Gazebo/Grey</name>
            </script>
            <ambient>1 1 1 1</ambient>
          </material>
          <meta>
            <layer>0</layer>
          </meta>
        </visual>
        <pose frame=''>-4.88 0.325 0 0 -0 0</pose>
        <self_collide>0</self_collide>
        <enable_wind>0</enable_wind>
        <kinematic>0</kinematic>
      </link>
      <link name='Wall_12'>
        <collision name='Wall_12_Collision'>
          <geometry>
            <box>
              <size>2.25 0.15 0.5</size>
            </box>
          </geometry>
          <pose frame=''>0 0 0.25 0 -0 0</pose>
          <max_contacts>10</max_contacts>
          <surface>
            <contact>
              <ode/>
            </contact>
            <bounce/>
            <friction>
              <torsional>
                <ode/>
              </torsional>
              <ode/>
            </friction>
          </surface>
        </collision>
        <visual name='Wall_12_Visual'>
          <pose frame=''>0 0 0.25 0 -0 0</pose>
          <geometry>
            <box>
              <size>2.25 0.15 0.5</size>
            </box>
          </geometry>
          <material>
            <script>
              <uri>file://media/materials/scripts/gazebo.material</uri>
              <name>Gazebo/Grey</name>
            </script>
            <ambient>1 1 1 1</ambient>
          </material>
          <meta>
            <layer>0</layer>
          </meta>
        </visual>
        <pose frame=''>-4.705 1.375 0 0 -0 1.5708</pose>
        <self_collide>0</self_collide>
        <enable_wind>0</enable_wind>
        <kinematic>0</kinematic>
      </link>
      <link name='Wall_16'>
        <collision name='Wall_16_Collision'>
          <geometry>
            <box>
              <size>0.5 0.15 0.5</size>
            </box>
          </geometry>
          <pose frame=''>0 0 0.25 0 -0 0</pose>
          <max_contacts>10</max_contacts>
          <surface>
            <contact>
              <ode/>
            </contact>
            <bounce/>
            <friction>
              <torsional>
                <ode/>
              </torsional>
              <ode/>
            </friction>
          </surface>
        </collision>
        <visual name='Wall_16_Visual'>
          <pose frame=''>0 0 0.25 0 -0 0</pose>
          <geometry>
            <box>
              <size>0.5 0.15 0.5</size>
            </box>
          </geometry>
          <material>
            <script>
              <uri>file://media/materials/scripts/gazebo.material</uri>
              <name>Gazebo/Grey</name>
            </script>
            <ambient>1 1 1 1</ambient>
          </material>
          <meta>
            <layer>0</layer>
          </meta>
        </visual>
        <pose frame=''>-4.88 -0.525 0 0 -0 0</pose>
        <self_collide>0</self_collide>
        <enable_wind>0</enable_wind>
        <kinematic>0</kinematic>
      </link>
      <link name='Wall_17'>
        <collision name='Wall_17_Collision'>
          <geometry>
            <box>
              <size>2 0.15 0.5</size>
            </box>
          </geometry>
          <pose frame=''>0 0 0.25 0 -0 0</pose>
          <max_contacts>10</max_contacts>
          <surface>
            <contact>
              <ode/>
            </contact>
            <bounce/>
            <friction>
              <torsional>
                <ode/>
              </torsional>
              <ode/>
            </friction>
          </surface>
        </collision>
        <visual name='Wall_17_Visual'>
          <pose frame=''>0 0 0.25 0 -0 0</pose>
          <geometry>
            <box>
              <size>2 0.15 0.5</size>
            </box>
          </geometry>
          <material>
            <script>
              <uri>file://media/materials/scripts/gazebo.material</uri>
              <name>Gazebo/Grey</name>
            </script>
            <ambient>1 1 1 1</ambient>
          </material>
          <meta>
            <layer>0</layer>
          </meta>
        </visual>
        <pose frame=''>-4.705 -1.45 0 0 -0 -1.5708</pose>
        <self_collide>0</self_collide>
        <enable_wind>0</enable_wind>
        <kinematic>0</kinematic>
      </link>
      <link name='Wall_19'>
        <collision name='Wall_19_Collision'>
          <geometry>
            <box>
              <size>2 0.15 0.5</size>
            </box>
          </geometry>
          <pose frame=''>0 0 0.25 0 -0 0</pose>
          <max_contacts>10</max_contacts>
          <surface>
            <contact>
              <ode/>
            </contact>
            <bounce/>
            <friction>
              <torsional>
                <ode/>
              </torsional>
              <ode/>
            </friction>
          </surface>
        </collision>
        <visual name='Wall_19_Visual'>
          <pose frame=''>0 0 0.25 0 -0 0</pose>
          <geometry>
            <box>
              <size>2 0.15 0.5</size>
            </box>
          </geometry>
          <material>
            <script>
              <uri>file://media/materials/scripts/gazebo.material</uri>
              <name>Gazebo/Grey</name>
            </script>
            <ambient>1 1 1 1</ambient>
          </material>
          <meta>
            <layer>0</layer>
          </meta>
        </visual>
        <pose frame=''>-5.055 -1.45 0 0 -0 -1.5708</pose>
        <self_collide>0</self_collide>
        <enable_wind>0</enable_wind>
        <kinematic>0</kinematic>
      </link>
      <link name='Wall_2'>
        <collision name='Wall_2_Collision'>
          <geometry>
            <box>
              <size>5 0.15 0.5</size>
            </box>
          </geometry>
          <pose frame=''>0 0 0.25 0 -0 0</pose>
          <max_contacts>10</max_contacts>
          <surface>
            <contact>
              <ode/>
            </contact>
            <bounce/>
            <friction>
              <torsional>
                <ode/>
              </torsional>
              <ode/>
            </friction>
          </surface>
        </collision>
        <visual name='Wall_2_Visual'>
          <pose frame=''>0 0 0.25 0 -0 0</pose>
          <geometry>
            <box>
              <size>5 0.15 0.5</size>
            </box>
          </geometry>
          <material>
            <script>
              <uri>file://media/materials/scripts/gazebo.material</uri>
              <name>Gazebo/Grey</name>
            </script>
            <ambient>1 1 1 1</ambient>
          </material>
          <meta>
            <layer>0</layer>
          </meta>
        </visual>
        <pose frame=''>14.925 0 0 0 -0 1.5708</pose>
        <self_collide>0</self_collide>
        <enable_wind>0</enable_wind>
        <kinematic>0</kinematic>
      </link>
      <link name='Wall_3'>
        <collision name='Wall_3_Collision'>
          <geometry>
            <box>
              <size>30 0.15 0.5</size>
            </box>
          </geometry>
          <pose frame=''>0 0 0.25 0 -0 0</pose>
          <max_contacts>10</max_contacts>
          <surface>
            <contact>
              <ode/>
            </contact>
            <bounce/>
            <friction>
              <torsional>
                <ode/>
              </torsional>
              <ode/>
            </friction>
          </surface>
        </collision>
        <visual name='Wall_3_Visual'>
          <pose frame=''>0 0 0.25 0 -0 0</pose>
          <geometry>
            <box>
              <size>30 0.15 0.5</size>
            </box>
          </geometry>
          <material>
            <script>
              <uri>file://media/materials/scripts/gazebo.material</uri>
              <name>Gazebo/Grey</name>
            </script>
            <ambient>1 1 1 1</ambient>
          </material>
          <meta>
            <layer>0</layer>
          </meta>
        </visual>
        <pose frame=''>0 2.425 0 0 -0 3.14159</pose>
        <self_collide>0</self_collide>
        <enable_wind>0</enable_wind>
        <kinematic>0</kinematic>
      </link>
      <link name='Wall_38'>
        <collision name='Wall_38_Collision'>
          <geometry>
            <box>
              <size>2 0.15 0.5</size>
            </box>
          </geometry>
          <pose frame=''>0 0 0.25 0 -0 0</pose>
          <max_contacts>10</max_contacts>
          <surface>
            <contact>
              <ode/>
            </contact>
            <bounce/>
            <friction>
              <torsional>
                <ode/>
              </torsional>
              <ode/>
            </friction>
          </surface>
        </collision>
        <visual name='Wall_38_Visual'>
          <pose frame=''>0 0 0.25 0 -0 0</pose>
          <geometry>
            <box>
              <size>2 0.15 0.5</size>
            </box>
          </geometry>
          <material>
            <script>
              <uri>file://media/materials/scripts/gazebo.material</uri>
              <name>Gazebo/Grey</name>
            </script>
            <ambient>1 1 1 1</ambient>
          </material>
          <meta>
            <layer>0</layer>
          </meta>
        </visual>
        <pose frame=''>5.185 -1.44 0 0 -0 -1.5708</pose>
        <self_collide>0</self_collide>
        <enable_wind>0</enable_wind>
        <kinematic>0</kinematic>
      </link>
      <link name='Wall_43'>
        <collision name='Wall_43_Collision'>
          <geometry>
            <box>
              <size>0.5 0.15 0.5</size>
            </box>
          </geometry>
          <pose frame=''>0 0 0.25 0 -0 0</pose>
          <max_contacts>10</max_contacts>
          <surface>
            <contact>
              <ode/>
            </contact>
            <bounce/>
            <friction>
              <torsional>
                <ode/>
              </torsional>
              <ode/>
            </friction>
          </surface>
        </collision>
        <visual name='Wall_43_Visual'>
          <pose frame=''>0 0 0.25 0 -0 0</pose>
          <geometry>
            <box>
              <size>0.5 0.15 0.5</size>
            </box>
          </geometry>
          <material>
            <script>
              <uri>file://media/materials/scripts/gazebo.material</uri>
              <name>Gazebo/Grey</name>
            </script>
            <ambient>1 1 1 1</ambient>
          </material>
          <meta>
            <layer>0</layer>
          </meta>
        </visual>
        <pose frame=''>5.36 -0.515 0 0 -0 0</pose>
        <self_collide>0</self_collide>
        <enable_wind>0</enable_wind>
        <kinematic>0</kinematic>
      </link>
      <link name='Wall_44'>
        <collision name='Wall_44_Collision'>
          <geometry>
            <box>
              <size>2 0.15 0.5</size>
            </box>
          </geometry>
          <pose frame=''>0 0 0.25 0 -0 0</pose>
          <max_contacts>10</max_contacts>
          <surface>
            <contact>
              <ode/>
            </contact>
            <bounce/>
            <friction>
              <torsional>
                <ode/>
              </torsional>
              <ode/>
            </friction>
          </surface>
        </collision>
        <visual name='Wall_44_Visual'>
          <pose frame=''>0 0 0.25 0 -0 0</pose>
          <geometry>
            <box>
              <size>2 0.15 0.5</size>
            </box>
          </geometry>
          <material>
            <script>
              <uri>file://media/materials/scripts/gazebo.material</uri>
              <name>Gazebo/Grey</name>
            </script>
            <ambient>1 1 1 1</ambient>
          </material>
          <meta>
            <layer>0</layer>
          </meta>
        </visual>
        <pose frame=''>5.535 -1.44 0 0 -0 -1.5708</pose>
        <self_collide>0</self_collide>
        <enable_wind>0</enable_wind>
        <kinematic>0</kinematic>
      </link>
      <link name='Wall_47'>
        <collision name='Wall_47_Collision'>
          <geometry>
            <box>
              <size>2.25 0.15 0.5</size>
            </box>
          </geometry>
          <pose frame=''>0 0 0.25 0 -0 0</pose>
          <max_contacts>10</max_contacts>
          <surface>
            <contact>
              <ode/>
            </contact>
            <bounce/>
            <friction>
              <torsional>
                <ode/>
              </torsional>
              <ode/>
            </friction>
          </surface>
        </collision>
        <visual name='Wall_47_Visual'>
          <pose frame=''>0 0 0.25 0 -0 0</pose>
          <geometry>
            <box>
              <size>2.25 0.15 0.5</size>
            </box>
          </geometry>
          <material>
            <script>
              <uri>file://media/materials/scripts/gazebo.material</uri>
              <name>Gazebo/Grey</name>
            </script>
            <ambient>1 1 1 1</ambient>
          </material>
          <meta>
            <layer>0</layer>
          </meta>
        </visual>
        <pose frame=''>5.175 1.365 0 0 -0 1.5708</pose>
        <self_collide>0</self_collide>
        <enable_wind>0</enable_wind>
        <kinematic>0</kinematic>
      </link>
      <link name='Wall_49'>
        <collision name='Wall_49_Collision'>
          <geometry>
            <box>
              <size>0.5 0.15 0.5</size>
            </box>
          </geometry>
          <pose frame=''>0 0 0.25 0 -0 0</pose>
          <max_contacts>10</max_contacts>
          <surface>
            <contact>
              <ode/>
            </contact>
            <bounce/>
            <friction>
              <torsional>
                <ode/>
              </torsional>
              <ode/>
            </friction>
          </surface>
        </collision>
        <visual name='Wall_49_Visual'>
          <pose frame=''>0 0 0.25 0 -0 0</pose>
          <geometry>
            <box>
              <size>0.5 0.15 0.5</size>
            </box>
          </geometry>
          <material>
            <script>
              <uri>file://media/materials/scripts/gazebo.material</uri>
              <name>Gazebo/Grey</name>
            </script>
            <ambient>1 1 1 1</ambient>
          </material>
          <meta>
            <layer>0</layer>
          </meta>
        </visual>
        <pose frame=''>5.35 0.315 0 0 -0 0</pose>
        <self_collide>0</self_collide>
        <enable_wind>0</enable_wind>
        <kinematic>0</kinematic>
      </link>
      <link name='Wall_51'>
        <collision name='Wall_51_Collision'>
          <geometry>
            <box>
              <size>2.25 0.15 0.5</size>
            </box>
          </geometry>
          <pose frame=''>0 0 0.25 0 -0 0</pose>
          <max_contacts>10</max_contacts>
          <surface>
            <contact>
              <ode/>
            </contact>
            <bounce/>
            <friction>
              <torsional>
                <ode/>
              </torsional>
              <ode/>
            </friction>
          </surface>
        </collision>
        <visual name='Wall_51_Visual'>
          <pose frame=''>0 0 0.25 0 -0 0</pose>
          <geometry>
            <box>
              <size>2.25 0.15 0.5</size>
            </box>
          </geometry>
          <material>
            <script>
              <uri>file://media/materials/scripts/gazebo.material</uri>
              <name>Gazebo/Grey</name>
            </script>
            <ambient>1 1 1 1</ambient>
          </material>
          <meta>
            <layer>0</layer>
          </meta>
        </visual>
        <pose frame=''>5.525 1.365 0 0 -0 1.5708</pose>
        <self_collide>0</self_collide>
        <enable_wind>0</enable_wind>
        <kinematic>0</kinematic>
      </link>
      <static>1</static>
    </model>
    <state world_name='default'>
      <sim_time>68 198000000</sim_time>
      <real_time>68 483826227</real_time>
      <wall_time>1579895048 749459437</wall_time>
      <iterations>68198</iterations>
      <model name='exp_empty_rooms'>
        <pose frame=''>-0.032029 0.002641 0 0 -0 0</pose>
        <scale>1 1 1</scale>
        <link name='Wall_0'>
          <pose frame=''>-14.957 0.002641 0 0 0 -1.5708</pose>
          <velocity>0 0 0 0 -0 0</velocity>
          <acceleration>0 0 0 0 -0 0</acceleration>
          <wrench>0 0 0 0 -0 0</wrench>
        </link>
        <link name='Wall_1'>
          <pose frame=''>-0.032029 -2.42236 0 0 -0 0</pose>
          <velocity>0 0 0 0 -0 0</velocity>
          <acceleration>0 0 0 0 -0 0</acceleration>
          <wrench>0 0 0 0 -0 0</wrench>
        </link>
        <link name='Wall_10'>
          <pose frame=''>-5.08703 1.37764 0 0 0 -1.5708</pose>
          <velocity>0 0 0 0 -0 0</velocity>
          <acceleration>0 0 0 0 -0 0</acceleration>
          <wrench>0 0 0 0 -0 0</wrench>
        </link>
        <link name='Wall_11'>
          <pose frame=''>-4.91203 0.327641 0 0 -0 0</pose>
          <velocity>0 0 0 0 -0 0</velocity>
          <acceleration>0 0 0 0 -0 0</acceleration>
          <wrench>0 0 0 0 -0 0</wrench>
        </link>
        <link name='Wall_12'>
          <pose frame=''>-4.73703 1.37764 0 0 -0 1.5708</pose>
          <velocity>0 0 0 0 -0 0</velocity>
          <acceleration>0 0 0 0 -0 0</acceleration>
          <wrench>0 0 0 0 -0 0</wrench>
        </link>
        <link name='Wall_16'>
          <pose frame=''>-4.91203 -0.522359 0 0 -0 0</pose>
          <velocity>0 0 0 0 -0 0</velocity>
          <acceleration>0 0 0 0 -0 0</acceleration>
          <wrench>0 0 0 0 -0 0</wrench>
        </link>
        <link name='Wall_17'>
          <pose frame=''>-4.73703 -1.44736 0 0 0 -1.5708</pose>
          <velocity>0 0 0 0 -0 0</velocity>
          <acceleration>0 0 0 0 -0 0</acceleration>
          <wrench>0 0 0 0 -0 0</wrench>
        </link>
        <link name='Wall_19'>
          <pose frame=''>-5.08703 -1.44736 0 0 0 -1.5708</pose>
          <velocity>0 0 0 0 -0 0</velocity>
          <acceleration>0 0 0 0 -0 0</acceleration>
          <wrench>0 0 0 0 -0 0</wrench>
        </link>
        <link name='Wall_2'>
          <pose frame=''>14.893 0.002641 0 0 -0 1.5708</pose>
          <velocity>0 0 0 0 -0 0</velocity>
          <acceleration>0 0 0 0 -0 0</acceleration>
          <wrench>0 0 0 0 -0 0</wrench>
        </link>
        <link name='Wall_3'>
          <pose frame=''>-0.032029 2.42764 0 0 -0 3.14159</pose>
          <velocity>0 0 0 0 -0 0</velocity>
          <acceleration>0 0 0 0 -0 0</acceleration>
          <wrench>0 0 0 0 -0 0</wrench>
        </link>
        <link name='Wall_38'>
          <pose frame=''>5.15297 -1.43736 0 0 0 -1.5708</pose>
          <velocity>0 0 0 0 -0 0</velocity>
          <acceleration>0 0 0 0 -0 0</acceleration>
          <wrench>0 0 0 0 -0 0</wrench>
        </link>
        <link name='Wall_43'>
          <pose frame=''>5.32797 -0.512359 0 0 -0 0</pose>
          <velocity>0 0 0 0 -0 0</velocity>
          <acceleration>0 0 0 0 -0 0</acceleration>
          <wrench>0 0 0 0 -0 0</wrench>
        </link>
        <link name='Wall_44'>
          <pose frame=''>5.50297 -1.43736 0 0 0 -1.5708</pose>
          <velocity>0 0 0 0 -0 0</velocity>
          <acceleration>0 0 0 0 -0 0</acceleration>
          <wrench>0 0 0 0 -0 0</wrench>
        </link>
        <link name='Wall_47'>
          <pose frame=''>5.14297 1.36764 0 0 -0 1.5708</pose>
          <velocity>0 0 0 0 -0 0</velocity>
          <acceleration>0 0 0 0 -0 0</acceleration>
          <wrench>0 0 0 0 -0 0</wrench>
        </link>
        <link name='Wall_49'>
          <pose frame=''>5.31797 0.317641 0 0 -0 0</pose>
          <velocity>0 0 0 0 -0 0</velocity>
          <acceleration>0 0 0 0 -0 0</acceleration>
          <wrench>0 0 0 0 -0 0</wrench>
        </link>
        <link name='Wall_51'>
          <pose frame=''>5.49297 1.36764 0 0 -0 1.5708</pose>
          <velocity>0 0 0 0 -0 0</velocity>
          <acceleration>0 0 0 0 -0 0</acceleration>
          <wrench>0 0 0 0 -0 0</wrench>
        </link>
      </model>
      <model name='ground_plane'>
        <pose frame=''>0 0 0 0 -0 0</pose>
        <scale>1 1 1</scale>
        <link name='link'>
          <pose frame=''>0 0 0 0 -0 0</pose>
          <velocity>0 0 0 0 -0 0</velocity>
          <acceleration>0 0 0 0 -0 0</acceleration>
          <wrench>0 0 0 0 -0 0</wrench>
        </link>
      </model>
      <light name='sun'>
        <pose frame=''>0 0 10 0 -0 0</pose>
      </light>
    </state>
    <gui fullscreen='0'>
      <camera name='user_camera'>
        <pose frame=''>77.5047 9.64372 47.1511 0 0.419644 -3.13498</pose>
        <view_controller>orbit</view_controller>
        <projection_type>perspective</projection_type>
      </camera>
    </gui>

  </model>
</sdf>

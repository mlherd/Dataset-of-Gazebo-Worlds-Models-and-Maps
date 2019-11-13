<?xml version="1.0" ?>
<sdf version="1.6">
  <model name="closed_box">
    <static>true</static>
    <link name="link">
<!--
      <collision name="collision">
        <geometry>
          <mesh>
            <scale>1.1 1.8 0.25</scale>
            <uri>model://closed_box_ariac/meshes/closed_box.obj</uri>
          </mesh>
        </geometry>
      </collision>
-->
      <visual name="visual">
        <geometry>
          <mesh>
            <scale>1.1 1.8 0.25</scale>
            <uri>model://closed_box_ariac/meshes/closed_box.obj</uri>
          </mesh>
        </geometry>
        <plugin name="toggle" filename="libToggleVisualPlugin.so">
          <initially_visible>false</initially_visible>
          <topic>~/drone_box_visual_toggle</topic>
        </plugin>
      </visual>
    </link>
  </model>
</sdf>

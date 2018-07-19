using System.Collections;
using System.Collections.Generic;
using UnityEngine;
using UnityEditor;

[CustomEditor(typeof(TileMap))]
public class TileMapEditor : Editor {

    public TileMap map;

    public override void OnInspectorGUI()
    {
        EditorGUILayout.BeginVertical();
        map.mapSize = EditorGUILayout.Vector2Field("Map Size", map.mapSize);
        EditorGUILayout.EndVertical();
    }

}

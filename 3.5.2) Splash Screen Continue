using System.Collections;
using System.Collections.Generic;
using UnityEngine;
using UnityEngine.SceneManagement;

public class ClicktoContinue : MonoBehaviour {

    public string scene;
    private bool loadlock;

	// Use this for initialization
	void Start () {
		
	}
	
	// Update is called once per frame
	void Update () {
        if (Input.GetMouseButtonDown(0) && !loadlock)
        {
            Loadscene();
        }
	}

    void Loadscene()
    {
        loadlock = true;
        SceneManager.LoadScene(scene);
    }
}

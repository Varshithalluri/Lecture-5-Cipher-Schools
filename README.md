using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class Variables_datatype : MonoBehaviour
{
    int myInt = 5;
    float myFloat = 10.5f;
    bool myBool = true;
    public string myString;
    // Start is called before the first frame update
    void Start()
    {
        Debug.Log("The value of myInt is : " + myInt);
        Debug.Log("The value of myFloat is : " + myFloat);
        Debug.Log("The value of myBool is : " + myBool);
        Debug.Log("The name is : " + myString);
    }

    // Update is called once per frame
    void Update()
    {
        
    }
}

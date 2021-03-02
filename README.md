# Asset-Sheets
Asset Sheets are plug-and-play CSS stylesheets for developing applications. Simply create a html element, link to the raw file for the css asset sheet you want to use under your head tag, and give it the class you want. To find out the class to use, please check out [figma](https://www.figma.com/file/iznYEZfkDNY3ebdaHq6NDr/Asset-Sheets?node-id=2%3A34)

## Slightly Neuromorphic Dark
**Note:** For html input elements, please give the input element a class of `input` and encapsulate it in a div with a class of `input_gradient`

## Very Neuromorphic Light
**Note:** For html input elements, please give the input element a class of `label` and encapsulate it in a div with a class of `inner_div`, in turn encapsulated with a div of  `outer_div` like:
 `

              <div class="outer_div">

                    <div class="inner_div">
                    
                        <input type="text" class="label" placeholder="input"> 
                        
                    </div>
                    
                </div> ` 

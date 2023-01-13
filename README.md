### Start with CDN links  
> Advisable to use CDN links for React and React DOM in the head tag  

Mistake 1: Not putting quotes around root in  
> document.getElementById("root")  

Mistake 2: Not updating script type to "text/babel"  
> You will get 'expected < token' error instead  

Mistake 3: Trying to render without wrapping in a div
> React wants to **render a single component** so having  
> Header component stacked over Main component won't do  
> Wrap'em around a div instead  

But then again, why stack all of them components in React.render()  
when you can absolutely use another component __App__ to do just that?  


# fib: feed it back
#### feedbackGPT 
linkedin API ? {...linkedInData} indeed API ? {...indeedData} // or JSON recipe for human submission

leveraging charting libraries like:
`<ReCharts/>` (and,or friends)

create "Data Visualizations" from the table below (pseudo-table rough-out):

```
{
job: string // not cluttering pseudotable-space with nullable values. The job name probably the only non-nullable field. 
location: string // i.e:     full address, zip, even just "NY, NY" 
pay: 
contact { phone: '...', email: '...' } 
                                   
isShortListed: bool
shortlist_count: // i.e. ("ur among last 4 ppl") // if interviewer relays numOfPpl in 2nd group between the first-larger-group & final-single-resolved-hired-person

my_notes: '',
assessments: [] // { type: '', overview: '', time: 60, pass: true, my_thoughts: '', interviewer_info: '', can_reapply: '', reapply_time: '' } 
}
```

// somewhat anecdotal but why project exists:
Can speak from recent experience doing 2 FE assessments at same time which never did 1 before:

ofc human can't bypass their own perception of their own data so even that gets between user-thoughts and user-chatGPT-promps but:
`User relays their perception of the interview-events to chatGPT, and also any information the interviewer (or events) provide to chatGPT as well`

* can chatGPT through API or (AI as params?) determine patterns distincted between linkedIn|indeed

* OR let's say - (actual example):
company B has the FE assessment available on a section of their website
if developer went home, created mockup of the assessment using same design approaches and AI|AI-API to: find gaps in best practices, and.., ... ...

same company B actually sat and gave feedback for almost an hour while same manager was juggling through candidates at the same time.

What if everything about company B besides their feedback was real.
Enough of the circumstances are replicable that one could put all the circumstances and inputs into a prompt:

response.feedback
// had no name so called it feedbackGPT and was kind of annoyed couldn't think of better name but didn't have time to think about a name
// after typing response.feedback call the program: "feeditback". Now Also doubles as acronym: "fib" tongue in cheek joke: The lie that you get feedback lol

